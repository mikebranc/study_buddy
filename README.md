# Study Buddy
This code is an adaptation of Shayne Parmelee's [elden agent](https://github.com/ShayneP/elden-agent)

🔗[Demo](https://youtu.be/1C56GHytjfM?si=QAP5p7bShC7QiJTx)

## To run the code
You will need to install the following libaries, make sure you use the latest versions:
```
pip install --upgrade \
livekit \
livekit-agents \
livekit-plugins-deepgram \
livekit-plugins-openai \
livekit-plugins-silero \
livekit-plugins-cartesia
```

You will also need api keys for deepgram, openai, livekit and silero. Once you have them you can export them like so:
```
export DEEPGRAM_API_KEY=<deepgram_api_key>
export OPENAI_API_KEY=<openai_api_key>
export LIVEKIT_API_SECRET=<livekit_secret>
export LIVEKIT_API_KEY=<livekit_api_key>  
export LIVEKIT_URL=<livekit_url>
export CARTESIA_API_KEY=<cartesia_api_key>
```

Once you have your dependencies installed, you simply run `python main.py dev`

As mentioned by Shayne, you also will want to use [OBS](https://obsproject.com/kb/virtual-camera-guide) for screen sharing. I had to restart chrome to get this to work. 

In order to get the front end working, you will want to use the [Livekit Agent's Playground](https://docs.livekit.io/agents/playground/). When that is running, you just need to hit connect in the top right and it should connect to the agent running in the backend.
