![Touch Grass](https://github.com/user-attachments/assets/dfa7ce19-05a0-4309-8026-aa166dc9773f)

You too can be reminded not to overwork your contribution graph by installing my [Touch Grass](https://github.com/lukeocodes/touch-grass) browser plugin.

<hr />

## Luke `@lukeocodes` Oliff

If you've landed on my profile, you're probably wondering what I do. Honestly, so are my family and my employer -- so you're in good company. I'm a seasoned software engineer with a focus on developer experience: I build and improve the tools and products that developers use every day, making them a little less painful and a lot more intuitive.

### If I was a container

```Dockerfile
# ADHD-Dockerfile

FROM multitasker:v1-rc.2

LABEL maintainer="luke@lukeoliff.com"

# Install focus tools
RUN apt-get update && apt-get install -y \
    adhd \
    executive-dysfunction \
    sticky-notes \
    coffee \
    software \
    fidget-spinners \
    gaming \
    ai

# Set up workspace
WORKDIR /home/luke

# ADD distractions
ADD https://bsky.app/profile/lukeocodes.dev /home/luke/bsky
ADD https://github.com/lukeocodes /home/luke/github

# GET work
ADD https://github.com/deepgram /home/luke/Projects/deepgram

# Start
CMD ["focus", "--start"]
ENTRYPOINT ["echo", "Starting session... ooh look, a squirrel!"]

# ADHD-Container running with 22515320994320 open tabs and 12 unfinished work tasks
```
