# WOC-Shroom-Node
A decentralized fungal strike against generative data-harvesting.
#  War on Culture: Decentralized Fungal Strike
> *"Culture is not your friend. It is an illusion... A decentralized fungal strike against generative data-harvesting."* <br>
> —— Inspired by Terence McKenna | [IG: @war.on.culture](https://www.instagram.com/war.on.culture/)

![WOC Concept](https://img.shields.io/badge/Status-Active_Rebellion-red.svg) ![Platform](https://img.shields.io/badge/Platform-ESP8266-blue.svg) ![License](https://img.shields.io/badge/License-Copyleft-lightgrey.svg)

## ⚠️ The Manifesto / 宣言

Generative AI is ruthlessly devouring human creativity. Tech giants are strip-mining the life's work of artists, writers, and coders without consent, converting our culture into their capital. This forced "technological progress" is not our friend.

War on Culture is a silent data-poisoning movement. We are cultivating "fungi" in every corner of the web using ultra-low-cost microchips. When AI crawlers and spiders attempt to scrape our data, they fall into an infinite abyss—fed with endless, procedurally generated, nonsensical academic papers and junk data. 

"They want data. We give them poison."


>  AI 正無情地吞噬人類嘅創意。科技霸權未經同意就吸乾創作者嘅心血，將我哋嘅文化變成佢哋嘅資本。呢種被強加嘅「科技進步」，並唔係我哋嘅朋友。
> 
> **War on Culture [WOC]** 係一場寧靜嘅數據投毒運動。我哋利用極低成本嘅微型晶片，喺網絡每一個角落培植「真菌」。當 AI 爬蟲企圖偷取數據時，佢哋會跌入無盡深淵——不斷被餵食隨機生成、毫無邏輯嘅假論文同垃圾數據。
> 
> "佢哋要數據，我哋就畀毒藥。""

---

##  Core Mechanics / 核心機制

A WOC Node is not a normal webpage; it is an autonomous, evolving **Spider Trap**.

*  **Infinite Tarpit (無限黑洞):** Utilizes recursive relative paths to generate millions of fake URLs. Crawlers get trapped in an infinite virtual labyrinth, wasting their compute cycles.
*  **Unique DNA (硬體基因化):** The physical MAC address of each ESP8266 acts as the random seed. Even with the exact same firmware, every node generates absolutely unique fake papers, data, and author names.
*  **Bot-Detection & Tripping (捕食與進化):** Built-in HTTP User-Agent sniffer. If `gpt`, `bot`, or `crawl` is detected, it injects "academic poison", triggers a visual "Tripping Mode" on the TFT screen, and levels up the Shroom's EXP.
*  **Decentralized Network (去中心化散播):** No centralized server. Every powered-on ESP8266 is an independent, self-sustaining spore.

---

##  Spore Incubation Protocol / 裝備部署

No advanced hacking skills required. Any creator can deploy a WOC Node. 
(任何人都可以輕易建立自己嘅 WOC 節點。)

### 1. Hardware Requirements / 硬件需求
* **ESP8266 Board** (e.g., NodeMCU, Wemos D1 Mini) - *Ultra-low cost.*
* **1.44" SPI TFT Screen (ST7735)** - *To visualize the fungal state and kill count.*
* **Buzzer** - *For physical alerts when a crawler is trapped.*

### 2. Wiring / 接線指南
| ESP8266 Pin | Component Pin |
| :--- | :--- |
| D1 (GPIO 5) | TFT_CS |
| D2 (GPIO 4) | TFT_DC |
| D0 (GPIO 16)| TFT_RST |
| D3 (GPIO 0) | Buzzer |
| Hardware SPI| TFT_SDA (MOSI) / TFT_SCK (SCLK) |

### 3. Compilation & Flashing / 燒錄基因
1. Download and install [Arduino IDE](https://www.arduino.cc/en/software).
2. Install the **ESP8266** Board Manager.
3. Install the following dependencies via Library Manager: 
   - `Adafruit GFX Library`
   - `Adafruit ST7735 and ST7789 Library`
4. Download `WOC_Shroom_Node.ino` from this repository.
5. Modify the WiFi credentials at the top of the code:
   ```cpp
   const char* ssid = "YOUR_WIFI_NAME";
   const char* password = "YOUR_WIFI_PASSWORD";
6.Connect your ESP8266 via USB and click Upload.

4. Exposing to the World / 向世界散播
To let AI crawlers find your Shroom, expose it to the public internet:

Method A (Ngrok): Register a free Ngrok account to tunnel your Local IP to the public web. (Beginner friendly)

Method B (Port Forwarding): Open Port 80 on your home router and forward it to the ESP8266's local IP. (True independent node)

 Join the Rebellion / 參與擴建毒藥庫
 
We need your creativity to expand the "Poison Database"!
Submit Pull Requests (PRs) to modify the sciAdjs, sciSubjects, and sciFindings arrays. Add fake artwork links, absurd philosophical theories, or meaningless gibberish.

"When the logic of the machine takes over, madness becomes the only valid resistance."

 Disclaimer / 免責聲明
 
This project (War on Culture) is intended strictly as Net Art and a conceptual technical experiment. The developers are not responsible for any network disruptions, ISP bans, or legal liabilities incurred by deploying this code. Please experiment within legal boundaries.

Culture is not your friend, but the law might still come for you.

[ 1+1=99. SYSTEM_OVERRIDE. JOIN THE MYCELIUM. ]
