## NOTES

### Original Repo
https://github.com/rampatra/wedding-website

### Blog
https://blog.rampatra.com/wedding-website

### Google Sheet
https://docs.google.com/spreadsheets/d/10Ke1bKJolqyK2QUb2kiiv9nn3G7_iYzDl2aBjD22yR4/edit?usp=sharing

### App Script
https://script.google.com/u/0/home/projects/1bcGiAAQArBqdhj1BNBay2uSw_kNLfYsFpNKjGlU1p-6g2Ky_IFxKYdQx/edit

### Docker
docker run -it --rm --mount type=bind,src=C:\Users\Seth\Desktop\repos\wedding-website,dst=/wedding-website -w=/wedding-website alpine:latest sh

### Build Commands
apk update && \
apk add --update nodejs npm && \
npm install --global gulp && \
npm install && \
gulp