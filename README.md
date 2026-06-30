[![Steam Workshop](https://img.shields.io/badge/Steam-Workshop-000000?style=for-the-badge&logo=steam)](YOUR_STEAM_WORKSHOP_URL)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-FF5E5B?style=for-the-badge&logo=ko-fi)](YOUR_KO_FI_URL)

# DayZ-TakistanSequel - TakistanPlus Terrain Addon
CE and Mission Files for TakistanSequel

# TakistanSequel

**TakistanSequel** is a map addon extending the original **TakistanPlus** terrain. It adds new points of interest, a different progression and loot distribution while still maintaining the core identity of the original map.

> **⚠️ Important:** This addon is a **derivative work** based on the original **TakistanPlus** mod by **CypeRevenge**.  Full credit belongs to the original author.

## 📦 Required Dependencies

This addon **will not work** without the following mods installed and loaded **before** TakistanSequel in your server's launch order:

1.  **TakistanPlus** (by CypeRevenge)
    *   The base terrain required for this sequel map.
    *   [Steam Workshop Link](https://steamcommunity.com/sharedfiles/filedetails/?id=2563233742)
2.  **Dabs Framework** (by Inclement Dab)
    *   Required for weather events and sandstorm mechanics inherited from the base map.
    *   [Steam Workshop Link](https://steamcommunity.com/sharedfiles/filedetails/?id=2545327648)

## 🚀 Installation

### Server Configuration

Server owners must configure the launch parameters carefully to ensure dependencies load correctly. 

1.  **Download** the latest release of **TakistanSequel**.
2.  **Install Dependencies**: Ensure `@TakistanPlus` and `@Dabs Framework` are installed on your server. 
3.  **Launch Parameters**: Add all mods to your startup command. **Order matters**:
    ```bash
    -mod=@Dabs Framework;@TakistanPlus;@TakistanSequel
    ```
    *Note: `TakistanPlus` must load before `TakistanSequel`.* 

4.  **Keys**: Copy the `.bikey` file from the `keys` folder of **TakistanSequel** (and dependencies) into your server's `keys` directory.

### Client Configuration

Players must subscribe to **all** required mods via the Steam Workshop or DayZ Launcher:
1.  Dabs Framework
2.  TakistanPlus
3.  TakistanSequel

## 🙏 Credits & Attribution

-   **Original Map**: **TakistanPlus** by **CypeRevenge**
-   **Framework**: **Dabs Framework** by **Inclement Dab**
*This project adheres to the licensing terms of the original TakistanPlus mod. All rights reserved by original authors where applicable.* 

## 🐛 Troubleshooting

-   **Map not loading?** Verify that `@TakistanPlus` is listed **before** `@TakistanSequel` in your `-mod` launch parameter. 
-   **Script Errors?** Check that **Dabs Framework** is updated to the latest version. 
