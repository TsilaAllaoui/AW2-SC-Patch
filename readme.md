Sure! Here's a more polished and appealing version of your README:

---

# ✅ Advance Wars 2 - SuperCard SD Fix Patch

This is an **IPS patch** designed for the **USA version** of *Advance Wars 2: Black Hole Rising*.
It fixes compatibility issues, allowing the game to run properly on **SuperCard SD** flash cartridges.

---

## 📥 How to Use

1. **Obtain a clean USA ROM** of *Advance Wars 2 – Black Hole Rising*.
2. **Apply the IPS patch** using any standard IPS patcher (e.g., Lunar IPS, Floating IPS).
3. **Load the patched ROM** onto your SuperCard SD.

---

## Why it works

The game try to call some subroutine when pressing start button on title screen, but for some reason SuperCard doesn't like it. So i bypassed them. 
The subroutine that caused problem were:
- **sub_0803B4DC**
- **sub_08030ED4**

## 🎮 Play and Enjoy!

You're now ready to command your troops without crashes or glitches on your SuperCard SD.
Enjoy the classic strategy experience!

---

## Credits

[eebit's partial rom decomp](https://github.com/Eebit/aw2bhr)
    - Used to find sub routine that caused crash

[Veslyquix's GBAFE Lua Tool]([https://github.com/Eebit/aw2bhr](https://github.com/Veslyquix/GBAFE-LuaUtilities))
    - Used to check what proc is running at a given time
