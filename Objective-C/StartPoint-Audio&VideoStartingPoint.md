根据不同的情况选择不同技术
- 如果要播放用户的ipod库中的音频，或者是播放本地或流视频，使用**Media Player**框架。该框架中的类已经支持发送音频和视频到AppleTV之类的AirPlay设备。
- 如果要简单的将图片或者视频剪辑加入到app中，使用**UIKit**框架中的专用类和方法。
- 如果是要进行基本的录音和回放，包括立体声平移、同步、计算，使用**AV Foundation**框架中的**audio**相关类。
- 如果要添加高性能的定位音乐播放到基于**OpenGL**的游戏或其他app，使用开源的**OpenAL**API。
- 如果要直接与音频或视频数据打交道--为了更好的性能或者是高级解决方案如VoIP、流、虚拟乐器或者是MIDI(乐器数字接口)--使用**AV Foundation**框架，**Assets Library**框架，各种**Core Audio**框架(包括Core Audio, Audio Toolbox, Audio Unit等框架)以及**Core MIDI**框架。

#开始和运行(Get Up and Running)
阅读以下资源以熟悉iOS音频开发：

1. 阅读**Multimedia Programming Guide**中"Using Audio"一节以学习iOS设备中的音频开发。确保理解了在"The Basics:Audio Codecs, Supported Audio Formats, and Audio Sessions"一节中介绍的audio session相关对象。
2. 阅读**avTouch**示例代码，该项目展示了如何使用**AVAudioPlayer**类来播放声音；阅读**SpeakHere**项目，该项目战士了基本的录音和播放；阅读**Audio UI Sounds(SysSound)**项目，该项目展示了如何触发震动和提示音和用户接口音效。
3. 下载**AddMusic**示例代码，该项目展示了怎样将ipod library播放库添加到你自己的app中。
4. 阅读**MPVolumeView Class Reference**，学习如何快速添加AirPlay功能到你自己的app中。

阅读以下资源以熟悉iOS视频开发：

0. 阅读**Multimedia Programming Guide**中"Using Video"一节以对iOS设备中得视频录制和播放有一个基本的了解。
1. 阅读**MoviePlayer**示例代码，该项目展示了强大的**MPMoviePlayerController**类。此类由于播放本地或者流视频；阅读**Using UIImagePickerController to Select Picture and Take Photos**项目，该项目展示了如何使用**UIKit**框架进行简单的视频和图像捕获。
2. 阅读**Camera Programming Topics for iOS**以学习如何使用UIImagePickerController类来拍摄照片和视频，以及浏览照片库。

#精通音频开发

- 如果要全面的理解**audio session**对象，以及他们如何决定了你的应用程序的音频表现，请阅读："Audio Session Programming Guide"
- 要了解app应该如何处理声音来满足用户的期望，阅读**iOS Human Interface Guidelines**中的"Sound"一节。
- 不管使用的是何种音频技术，用户都希望能够在多任务UI中使用系统控制来播放和暂停音频。
- 阅读**iPod Library Access Programming Guide**以及**Media Player Framework Referrence**来使用iPod库。
- 要学习如何使用OpenAL来播放音频，阅读**oalTouch**项目。


#精通视频开发

