# Tawuniya Power BI Themes

A collection of Power BI JSON theme files for Tawuniya dashboards curated by the data office, organized by line of business to ensure visual consistency and brand alignment

## Included Themes

- **[Tawuniya Main Brand - Light Mode](./Tawuniya%20Main%20Brand%20-%20Light%20Mode.json)**  
  The primary theme following tawuniya's main brand colors

- **[Tawuniya Data Theme - Light Mode](./Tawuniya%20Data%20Theme%20-%20Light%20Mode.json)** / **[Tawuniya Data Theme - Dark Mode](./Tawuniya%20Data%20Theme%20-%20Dark%20Mode.json)**

The primary theme used in data office dashboards reflecting our data office colors

### Line of Business JSON Themes

- **[General Theme - Light Mode](./Line%20Of%20Business%20JSON%20Themes/General%20Theme%20-%20Light%20Mode.json)** / **[General Theme - Dark Mode](./Line%20Of%20Business%20JSON%20Themes/General%20Theme%20-%20Dark%20Mode.json)**

  Tailored colors and formatting for the General line of business

- **[Health Theme - Light Mode](./Line%20Of%20Business%20JSON%20Themes/Health%20Theme%20-%20Light%20Mode.json)** / **[Health Theme - Dark Mode](./Line%20Of%20Business%20JSON%20Themes/Health%20Theme%20-%20Dark%20Mode.json)**

  Tailored colors and formatting for the Health line of business

- **[Motor Theme - Light Mode](./Line%20Of%20Business%20JSON%20Themes/Motor%20Theme%20-%20Light%20Mode.json)** / **[Motor Theme - Dark Mode](./Line%20Of%20Business%20JSON%20Themes/Motor%20Theme%20-%20Dark%20Mode.json)**

  Tailored colors and formatting for the Mobility line of business

### Assets

This folder contains assets developers may need, including dark- and light-mode Tawuniya logos, line-of-business logos, and the official icon for each business line

**Tawuniya LOB Logos**

|                | General                                                                                                    | Health                                                                                                    | Mobility                                                                                                      |
| -------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Dark Mode**  | [ General - Dark Mode](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20General%20-%20Dark%20Mode.png)   | [ Health - Dark Mode](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20Health%20-%20Dark%20Mode.png)    | [ Mobility - Dark Mode](./Assets/LOB%20Logos/Dark%20Mode/Tawuniya%20Logo%20Mobility%20-%20Dark%20Mode.png)    |
| **Light Mode** | [General - Light Mode](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20General%20-%20Light%20Mode.png) | [ Health - Light Mode](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20Health%20-%20Light%20Mode.png) | [ Mobility - Light Mode](./Assets/LOB%20Logos/Light%20Mode/Tawuniya%20Logo%20Mobility%20-%20Light%20Mode.png) |

---
## 🚀 How to Use the Tawuniya Power BI Themes

Follow these steps to start building dashboards using Tawuniya’s official Power BI design framework.  

---

### 🧩 **Using the Ready-Made Templates**

1. **Download the ATLAS Library File**  
   Get the latest `.pbix` file from the repository — this serves as your starting point and includes all layouts, visuals, and styles.  

2. **Open the File in Power BI Desktop**  
   Launch Power BI Desktop and open the downloaded ATLAS library file.  

3. **Download the Required Theme from GitHub**  
   Navigate to the [Included Themes](#included-themes) section in the README and download the `.json` theme that fits your use case (Light/Dark mode, or LOB-specific).  

4. **Apply the Theme**  
   In Power BI Desktop, go to **View → Themes → Browse for Themes...**, and select the downloaded `.json` file.  

5. **Choose a Template Page**  
   Pick the layout that fits your dashboard type (executive, operations, summary, etc.).  

6. **Make Necessary Design Adjustments**  
   Update titles, headers, KPIs, or colors as needed while keeping the structure aligned with the theme’s design system.  

7. **Connect Your Data**  
   Replace the sample data connections with your actual data sources.  

8. **Remove Unused Pages**  
   Delete all template pages that are not required for your final dashboard.  

9. **Publish the Dashboard**  
   Once finalized, publish your dashboard to Power BI Service or your designated workspace.  

---

### 🧱 **Building From Scratch (Without Templates)**

If you prefer to design a new dashboard layout:

1. **Use the Visuals Section**  
   Open the **Visuals** page in the ATLAS library — it contains preformatted visuals that are already aligned with Tawuniya’s brand and grid system.  

2. **Copy and Paste Needed Visuals**  
   Copy the visuals you need from the Visuals section and paste them onto your new blank page.  

3. **Apply the Preferred Theme**  
   Choose a `.json` theme file (Colorful, Main Brand, or LOB-specific) to maintain color and typography consistency.  

4. **Connect Your Data and Customize Layouts**  
   Bind your visuals to data fields and adjust placements using the Power BI Desktop grid guide for alignment.  

5. **Publish When Ready**  
   Finalize your design and publish to Power BI Service.  

---

> 💡 **Tip:** Always use the provided grid guide (`Desktop Grid.svg`) as a background while designing to ensure proper spacing, symmetry, and visual harmony.

---

## How To Use Themes in Power BI Desktop

1. Download the desired `.json` file
2. Open Your Report
3. In Power BI Desktop, go to **View > Themes > Browse for themes...**
4. Select the downloaded file to apply the theme across your report

##### For Further Instructions Follow The Guide Below: https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes

---

## Power BI Desktop Grid

Use this grid as a background in Power BI to guide spacing, alignment, and margins so dashboards stay uniform

![Power BI Desktop Grid](./Assets/Desktop%20Grid.svg)

**How To Use**

1. In Power BI Desktop, select an empty area on the canvas and open **Format > Canvas background**
2. Choose **Image** and browse to `Desktop Grid.svg`
3. Set **Image fit** to **Fill** ensure it adapts to different canvas sizes, and adjust **Transparency** to **50%** so visuals are readable
4. Align visuals to the columns and maintain consistent padding to the grid

---

## [➥ Power BI Useful Custom Visuals List](./Power%20BI%20Useful%20Custom%20Visuals.md)

A curated list of ***free useful Power BI custom visuals*** that are completely **free to use** and designed to serve specific analytical and storytelling scenarios.

These visuals extend beyond the default Power BI capabilities—some address niche use cases not achievable through standard visuals, while others enhance the **visual appeal and interactivity** of dashboards. 

## License

All rights reserved for Tawuniya Insurance.

© 2025 ATLAS Power Bl Data Visualization Library. All rights reserved.

