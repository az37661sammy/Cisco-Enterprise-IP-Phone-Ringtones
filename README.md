# 📞 Cisco Enterprise IP Phone Ringtones

A collection of wideband (.rwb) ringtone resources for Cisco Enterprise IP Phones, FreePBX, Cisco Unified Communications Manager (CUCM), and custom TFTP provisioning servers.

## 🎵 Ringtone Collection

| Ringtone | Filename |
|---|---|
| Ascent | Ascent.rwb |
| Busy Hope | Busy_Hope.rwb |
| Calculation | Calculation.rwb |
| Callback | Callback.rwb |
| Delight | Delight.rwb |
| Evolve | Evolve.rwb |
| In Room Leaves | InRoom_Leaves.rwb |
| Incoming EQ | Incoming_EQ.rwb |
| Mellow | Mellow.rwb |
| Mischief | Mischief.rwb |
| Mobile Dreams | Mobile_Dreams.rwb |
| Mobile Secret | Mobile_Secret.rwb |
| OpenPlan Cloud | OpenPlan_Cloud.rwb |
| OpenPlan Discreet | OpenPlan_Discreet.rwb |
| Playful | Playful.rwb |
| Reflections | Reflections.rwb |
| Ringer | Ringer.rwb |
| Ripples | Ripples.rwb |
| Sunrise | Sunrise.rwb |
| Vibes | Vibes.rwb |

## 📥 Download

Select the green **Code** button at the top of this repository and click **Download ZIP**.

## ⚙️ Installation

### FreePBX / Custom TFTP Server

1. Download and extract the files.
2. Upload the ringtone files to your phone's TFTP provisioning directory.
3. Upload the Ringlist-wb.xml configuration file.
4. Restart your Cisco IP Phone.
5. Navigate to the ringtone settings.
6. Select your preferred ringtone.

### Cisco Unified Communications Manager (CUCM)

Upload authorized ringtone files and the appropriate ringtone XML configuration using Cisco Unified OS Administration. Follow the provisioning requirements for your phone model and CUCM version.

## 📱 Intended Compatibility

- Cisco 7800 Series
- Cisco 8800 Series
- Cisco 8900 Series
- Cisco 9900 Series


### Cisco 7900 Series Compatibility

> [!NOTE]
> If you are using a Cisco 7900 Series IP Phone, such as the
> Cisco 7942, 7945, 7962, or 7965, you must convert the
> wideband (.rwb) ringtone files to the supported .raw format
> before installing them on your phone.

The converted ringtone files must meet the following requirements:

- File extension: .raw
- Audio encoding: 8-bit G.711 μ-law (u-law)
- Sample rate: 8000 Hz
- Channels: Mono
- Maximum length: 16,080 samples (approximately 2 seconds)

You must also use a compatible Ringlist.xml configuration
instead of Ringlist-wb.xml and update the filenames from
.rwb to .raw.

Simply renaming the file extension will not work.
The audio must be properly converted.


Compatibility depends on the phone model, firmware, audio format, and ringtone duration. Not all models have been tested.

## 🛠️ Supported Environments

- FreePBX
- Asterisk
- Cisco Unified Communications Manager (CUCM)
- Custom TFTP provisioning servers

## 🐛 Issues and Contributions

If you encounter a problem or have a suggestion, please open an issue in this repository.

## ⚠️ Disclaimer

This is an unofficial community project and is not affiliated with, sponsored by, or endorsed by Cisco Systems, Inc.

Cisco trademarks and original ringtone audio belong to their respective owners. Audio must only be distributed with appropriate authorization.

---

Thank you for visiting this repository!
