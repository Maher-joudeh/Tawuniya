
## **Power BI Theme JSON to Design Tokens Mapping Table**

| Component | JSON Property Path | Alias Token (Light Mode) | Option Token (Light Mode) | Alias Token (Dark Mode) | Option Token (Dark Mode) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| **Visuals (Global)** |  |  |  |  |  |
| Value Axis Gridline Color | `visualStyles/valueAxis[^0].gridlineColor` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| Category Axis Gridline Color | `visualStyles/categoryAxis[^0].gridlineColor` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| Value Axis Label Color | `visualStyles/valueAxis[^0].labelColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| Category Axis Label Color | `visualStyles/categoryAxis[^0].labelColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| Legend Font Color | `visualStyles/legend[^0].fontColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| Visual Title Font Color | `visualStyles/title[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Visual Subtitle Font Color | `visualStyles/subTitle[^0].fontColor` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Visual Background Color | `visualStyles/background[^0].color` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Visual Border Color | `visualStyles/border[^0].color` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| Drop Shadow Color | `visualStyles/dropShadow[^0].color` | `black-solid` | `Color.Neutral.Dark Navy` | `black-solid` | `Pure Black` |
| Totals Font Color | `visualStyles/totals[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Page** |  |  |  |  |  |
| Page Canvas Background | `visualStyles.page/background[^0].color` | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| Filter Pane Background | `visualStyles.page/outspacePane[^0].backgroundColor` | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| Filter Pane Foreground | `visualStyles.page/outspacePane[^0].foregroundColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Filter Card Background (Applied) | `visualStyles.page/filterCard[^0][$id=Applied].backgroundColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Filter Card Foreground (Applied) | `visualStyles.page/filterCard[^0][$id=Applied].foregroundColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Filter Card Input Box | `visualStyles.page/filterCard[^0][$id=Applied].inputBoxColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.800` |
| **Card Visual** |  |  |  |  |  |
| Card Accent Bar Color | `visualStyles.cardVisual/accentBar[^0][$id=default].color` | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| Card Border Color | `visualStyles.cardVisual/border[^0].color` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| Card Divider Color | `visualStyles.cardVisual/divider[^0][$id=default].dividerColor` | `border-secondary` | `Color.Neutral.200` | `border-secondary` | `Color.Neutral.700` |
| Card Label Font Color | `visualStyles.cardVisual/label[^0][$id=default].fontColor` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Card Title Font Color | `visualStyles.cardVisual/title[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Card Title Background | `visualStyles.cardVisual/title[^0].background` | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| Card Value Font Color | `visualStyles.cardVisual/value[^0][$id=default].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Card Reference Label Background | `visualStyles.cardVisual/referenceLabel[^0][$id=default].backgroundColor` | `background-brand` (with transparency) | `Color.Brand.500` @ 7.5% | `background-brand` (with transparency) | `Color.Brand.500` @ 15% |
| Card Reference Label Title | `visualStyles.cardVisual/referenceLabelTitle[^0][$id=default].titleFontColor` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Card Reference Label Value | `visualStyles.cardVisual/referenceLabelValue[^0][$id=default].valueFontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Card Reference Label Detail | `visualStyles.cardVisual/referenceLabelDetail[^0][$id=default].detailFontColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| **Table (tableEx)** |  |  |  |  |  |
| Table Column Header Background | `visualStyles.tableEx/columnHeaders[^0].backColor` | `background-brand` | `Color.Brand.50` | `background-secondary` | `Color.Neutral.800` |
| Table Column Header Font Color | `visualStyles.tableEx/columnHeaders[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Table Grid Outline Color | `visualStyles.tableEx/grid[^0].outlineColor` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.700` |
| Table Values Font Color | `visualStyles.tableEx/values[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-secondary` | `Color.Neutral.300` |
| Table Values Background (Primary) | `visualStyles.tableEx/values[^0].backColorPrimary` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Table Values Background (Secondary) | `visualStyles.tableEx/values[^0].backColorSecondary` | `background-primary` | `Color.Neutral.white` | `background-secondary` | `Color.Neutral.800` |
| Table Title Font Color | `visualStyles.tableEx/title[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Table Total Font Color | `visualStyles.tableEx/total[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Pivot Table** |  |  |  |  |  |
| Pivot Grid Outline Color | `visualStyles.pivotTable/grid[^0].outlineColor` | `border-secondary` | `Color.Neutral.200` | `border-secondary` | `Color.Neutral.700` |
| Pivot Row Headers Font Color | `visualStyles.pivotTable/rowHeaders[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Pivot Values Font Color | `visualStyles.pivotTable/values[^0].fontColor` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Pivot Column Headers Font Color | `visualStyles.pivotTable/columnHeaders[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Slicer** |  |  |  |  |  |
| Slicer Items Background | `visualStyles.slicer/items[^0].background` | `background-secondary` | `Color.Neutral.25` | `background-primary` | `Color.Neutral.900` |
| Slicer Items Font Color | `visualStyles.slicer/items[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Slicer Slider Color | `visualStyles.slicer/slider[^0].color` | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| Slicer Handle Fill Color | `visualStyles.slicer/slider[^0].handleFillColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Slicer Handle Border Color | `visualStyles.slicer/slider[^0].handleBorderColor` | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| Slicer Date Font Color | `visualStyles.slicer/date[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Action Button** |  |  |  |  |  |
| Button Border Color | `visualStyles.actionButton/border[^0].color` | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.700` |
| Button Fill Color (Default) | `visualStyles.actionButton/fill[^0][$id=default].fillColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Button Fill Color (Hover) | `visualStyles.actionButton/fill[^0][$id=hover].fillColor` | `background-primary` | `Color.Neutral.white` | `background-secondary` | `Color.Neutral.800` |
| Button Fill Color (Selected) | `visualStyles.actionButton/fill[^0][$id=selected].fillColor` | `background-brand` (with transparency) | `Color.Brand.500` @ 25% | `background-brand` (with transparency) | `Color.Brand.500` @ 25% |
| Button Text Font Color | `visualStyles.actionButton/text[^0][$id=default].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Button Icon Line Color | `visualStyles.actionButton/icon[^0][$id=hover].lineColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Bookmark Navigator** |  |  |  |  |  |
| Bookmark Fill Color (Default) | `visualStyles.bookmarkNavigator/fill[^0][$id=default].fillColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Bookmark Fill Color (Selected) | `visualStyles.bookmarkNavigator/fill[^0][$id=selected].fillColor` | `background-primary` | `Color.Neutral.white` | `background-secondary` | `Color.Neutral.800` |
| Bookmark Accent Bar Color | `visualStyles.bookmarkNavigator/accentBar[^0][$id=default].color` | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| Bookmark Outline Color | `visualStyles.bookmarkNavigator/outline[^0][$id=default].lineColor` | `border-tertiary` | `Color.Neutral.100` | `border-secondary` | `Color.Neutral.700` |
| Bookmark Text Color (Default) | `visualStyles.bookmarkNavigator/text[^0][$id=default].fontColor` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Bookmark Text Color (Selected) | `visualStyles.bookmarkNavigator/text[^0][$id=selected].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Charts (All)** |  |  |  |  |  |
| Chart Data Label Color | `visualStyles.clusteredColumnChart/labels[^0].color` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Donut/Pie Chart Label Color | `visualStyles.donutChart/labels[^0].color` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Scatter Chart Legend Color | `visualStyles.scatterChart/legend[^0].fontColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| Line Chart Axis Color | `visualStyles.lineChart/categoryAxis[^0].labelColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| **Gauge** |  |  |  |  |  |
| Gauge Callout Value Color | `visualStyles.gauge/calloutValue[^0].color` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Gauge Labels Color | `visualStyles.gauge/labels[^0].color` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| Gauge Target Color | `visualStyles.gauge/target[^0].fontColor` | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| **Textbox** |  |  |  |  |  |
| Textbox Font Color | `visualStyles.textbox/general[^0].paragraphs[^0].textRuns[^0].fontColor` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| **Shape** |  |  |  |  |  |
| Shape Fill Color | `visualStyles.shape/fill[^0].fillColor` | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| Shape Outline Color | `visualStyles.shape/outline[^0].lineColor` | `border-primary` | `Color.Neutral.300` | `border-primary` | `Color.Neutral.600` |
| **Data Colors** |  |  |  |  |  |
| Data Color 1 | `dataColors[^0]` | `data-colors.category-1` | `Color.TAWN.Light.01` | `data-colors.category-1` | `Color.TAWN.Dark.01` |
| Data Color 2 | `dataColors[^1]` | `data-colors.category-2` | `Color.TAWN.Light.02` | `data-colors.category-2` | `Color.TAWN.Dark.02` |
| Data Color 3 | `dataColors[^2]` | `data-colors.category-3` | `Color.TAWN.Light.03` | `data-colors.category-3` | `Color.TAWN.Dark.03` |
| Data Color 4 | `dataColors[^3]` | `data-colors.category-4` | `Color.TAWN.Light.04` | `data-colors.category-4` | `Color.TAWN.Dark.04` |
| Data Color 5 | `dataColors[^4]` | `data-colors.category-5` | `Color.TAWN.Light.05` | `data-colors.category-5` | `Color.TAWN.Dark.05` |
| Data Color 6 | `dataColors[^5]` | `data-colors.category-6` | `Color.TAWN.Light.06` | `data-colors.category-6` | `Color.TAWN.Dark.06` |
| Data Color 7 | `dataColors[^6]` | `data-colors.category-7` | `Color.TAWN.Light.07` | `data-colors.category-7` | `Color.TAWN.Dark.07` |
| Data Color 8 | `dataColors[^7]` | `data-colors.category-8` | `Color.TAWN.Light.08` | `data-colors.category-8` | `Color.TAWN.Dark.08` |
| **Sentiment Colors** |  |  |  |  |  |
| Success/Good | `good` | `text-success` | `Color.Success.700` | `text-success` | `Color.Success.300` |
| Error/Bad | `bad` | `text-error` | `Color.Error.700` | `text-error` | `Color.Error.300` |
| Warning/Center | `center` | `text-warning` | `Color.Warning.700` | `text-warning` | `Color.Warning.300` |
| Neutral | `neutral` | `text-disabled` | `Color.Neutral.400` | `text-disabled` | `Color.Neutral.500` |
| Maximum (Gradient) | `maximum` | `text-brand-solid` | `Color.Brand.500` | `text-brand` | `Color.Brand.400` |
| Minimum (Gradient) | `minimum` | `background-warning` | `Color.Warning.50` | `background-warning` | `Color.Warning.900` |
| **Typography** |  |  |  |  |  |
| Font Family (All) | `textClasses/fontFace` | `font-family-secondary` | `Font.Family.Secondary` (Tawuniya) | `font-family-secondary` | `Font.Family.Secondary` (Tawuniya) |
| Primary Text Color | `textClasses.callout.color` | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| Secondary Text Color | `textClasses.label.color` | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |

This table provides complete traceability from Power BI JSON properties → Semantic Alias Tokens → Option (Base) Tokens for both light and dark modes!
