# ADOBE PREMIERE PRO 2022 PROXY Guide

These are the exact settings you need to get your computer editing even the highest resolution video super fast in Premiere Pro.

---

## 💻 PREMIERE PRO PROXY SETTINGS

Here are the steps to enable proxies of your video footage using Premiere’s built-in presets:

1. 🔧 Open Premiere Pro and import all of your video footage.
2. 🔄 Select the clips that you want to make proxies for in the Project panel by either clicking and dragging or selecting the first clip, holding Shift, then selecting the last clip.
3. 🔐 Right-click on a clip and select **Proxy > Create Proxies**.
4. 🎥 For **Format**, select **Quicktime**.
5. 📏 For **Preset**, select **ProRes Low Resolution Proxy**.
6. 🆓 Check the **Add Watermark** box.
7. 🏢 Leave the destination as **Next To Original Media, in prox folder**.
8. 🔄 Press **OK**.
9. 🌐 Premiere will open Media Encoder and begin rendering proxies for all of your video clips. Depending on the number of clips you have and the speed of your computer, this could take a while. Consider creating proxies overnight if necessary.
10. 🔸 Once proxies are created, enable them by clicking the **Toggle Proxies** icon in the Program panel. If you do not see the Toggle Proxies icon, click the **plus icon** in the bottom right of the panel and click and drag the Toggle Proxies Icon down next to the play button in the bottom middle of the panel.
11. 🔹 Your proxies will now be enabled, and your footage will playback very smoothly. Check the proxy watermark in the bottom left of your video clip and the proxy icon on the clip in the timeline to ensure the proxies are enabled.
12. 💾 When exporting your finished video file, you do not need to disable proxies; Premiere will do that automatically and use your native video files when exporting.

---

## 🚀 HOW TO BATCH SLOW MOTION AND SAVE TIME

In the past, I recommended interpreting your video clips that you wanted to make slow motion, but in the newer versions of Premiere Pro, there is a new way that is even faster and easier.

If you have a lot of video clips that you want to make slow motion, follow these steps:

1. 🔑 Right-click on any blank area in the Project panel and select **New Search Bin**.
2. 🔼 In the top left dropdown, change **All Metadata** to **Frame Rate**, and in the top right search box, enter the frame rate of the footage that you want to slow down.
    - For 30fps footage, enter **29.97**.
    - For 60fps footage, enter **59.94**.
    - For 120fps footage, enter **119.88**.
3. 🔢 This will create a new bin in the Project panel that has all of the video clips that you imported at that frame rate.
4. 🔄 Select all of the clips in this new bin that you want to make slow motion by either clicking and dragging or selecting the first clip, holding Shift, then selecting the last clip.
5. 🔐 Right-click on one of the clips and select **Speed/Duration**.
6. 🔄 Enter the following percentages depending on the frame rate of your footage:
    - For 30fps footage, enter **80%**.
    - For 60fps footage, enter **40%**.
    - For 120fps footage, enter **20%**.

This will slow down all of your clips at once and will also slow down your proxy files too, so everything matches up perfectly! You can then drag your footage to the timeline and edit it as you normally would.

---

### 💡 Note:
Do not batch slow motion your footage using this technique to clips that you have already started editing on your timeline, as this can make the timing of your cuts change.

