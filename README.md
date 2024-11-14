![1500x500](https://github.com/user-attachments/assets/6bcf207a-3740-42d6-9e9b-106f1ec4493b)

Contain me!

```Dockerfile
# ADHD-Dockerfile

FROM multitasker:latest

LABEL maintainer="luke@lukeoliff.com"

# Install focus tools
RUN apt-get update && apt-get install -y \
    adhd \
    executive-dysfunction \
    sticky-notes \
    coffee \
    software \
    fidget-spinners \
    gaming

# Set up workspace
WORKDIR /home/luke

# ADD distractions
ADD https://x.com/lukeocodes /home/luke/x
ADD https://github.com/lukeocodes /home/luke/github

# GET work
RUN git clone git@github.com:deepgram-devs/deepgram-conversational-demo.git
RUN git clone git@github.com:deepgram/deepgram-js-sdk.git
RUN git clone git@github.com:deepgram-starters/nextjs-live-transcription.git
RUN git clone git@github.com:deepgram-devs/react-nowplaying.git

# CMD to run focus tools (which get ignored)
CMD ["focus", "--start"]

# Entry point (where it all goes off track)
ENTRYPOINT ["echo", "Starting focus session... ooh look, a squirrel!"]

# End result
# ADHD-Container running with 22515320994320 open tabs and 12 unfinished work tasks
```
