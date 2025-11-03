# apple-clock-timer-bug-report:

# iOS Clock App Timer Bug – Picker Freezes at 16:39

## 🐞 Summary

On iOS 18 (build 26.x), the native **Clock app > Timer picker** freezes at exactly **16 hours and 39 minutes** when the user scrolls rapidly through the timer picker wheels. The UI becomes unresponsive beyond that point until the user exits and reopens the picker.

## 📱 Device & System Info

- Device: iPhone [your model]
- iOS Version: 18.0 (build 26.x)
- Clock app: Native iOS Clock (Timer tab)

## 🔁 Steps to Reproduce

1. Open the **Clock app**
2. Go to the **Timer** tab
3. Tap to set a custom timer duration
4. Flick-scroll rapidly through the hour and/or minute wheels
5. Picker freezes visually and functionally at **16:39**

## ✅ Expected Behavior

- The picker should allow valid times up to 23:59.
- It should stop scrolling cleanly or cap at a maximum time.
- It should not freeze or become unresponsive.

## ❌ Actual Behavior

- Picker freezes at 16:39
- Further input has no effect
- App requires reset to work properly

## 🧪 Notes

This issue was present in earlier iOS versions as well, indicating a long-standing bug in the native UI component.

I have reported this bug to Apple via [Feedback Assistant](https://feedbackassistant.apple.com).

## 🎥 (Optional)

If you want to test it yourself, record the screen while scrolling rapidly in the Timer picker.

## 📌 Why I Logged This

I document bugs I discover in public apps to show my process, attention to detail, and interest in improving user experience. If you're hiring someone who likes to dig into systems and find edge cases — you're looking at them.
