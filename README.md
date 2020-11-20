# twitter-voice
Twitterボイスのクローン | a clone of twitter voice feature

Twitter Voice is a new feature that rolling randomly on selected user.
Think of voice memo that mostly available on any phone by default, but instead of saving it as audio file, its converted into a video.
Why does is it converted into a video? Simply because its one of SNS feature so it has to be more visual.

![Twitter Voice preview](./documentation/images/video-preview.svg)

## Visual Requirements
- Visually displaying the length of audio on left bottom
- `Watermark` on right bottom
- Displaying image / profile picture in the center
- Displaying visual effect behind the profile picture such as 4 circle shrinks and expands over time
- Displaying animation of audio icon

## Future Feature
- Twitter SSO (fetch username and profile picture from Twitter)
- Option to tweet directly from application without downloading it

## Note
Twitter Voice seems fluid dynamic and cool, but actually it's pretty simple. They got tricks that makes it looks dyanmic. For example:
- Animation behind the profile picture, its actually static (not following the audio wave)
- Time displayed on left bottom is static, its showing the length of audio. I thought it was something like any music streaming platform that provides how many seconds or minutes left to listen.

## Reference
- Official Voice Feature on Twitter
