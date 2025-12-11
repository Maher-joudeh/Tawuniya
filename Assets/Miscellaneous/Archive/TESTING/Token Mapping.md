
## **Power BI Theme JSON → Design Tokens Mapping (Hierarchical Structure)**

### **1. Root Level Properties**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `dataColors[^0]` | Root | `data-colors.category-1` | `Color.TAWN.Light.01` | `data-colors.category-1` | `Color.TAWN.Dark.01` |
| `dataColors[^1]` | Root | `data-colors.category-2` | `Color.TAWN.Light.02` | `data-colors.category-2` | `Color.TAWN.Dark.02` |
| `dataColors[^2]` | Root | `data-colors.category-3` | `Color.TAWN.Light.03` | `data-colors.category-3` | `Color.TAWN.Dark.03` |
| `dataColors[^3]` | Root | `data-colors.category-4` | `Color.TAWN.Light.04` | `data-colors.category-4` | `Color.TAWN.Dark.04` |
| `dataColors[^4]` | Root | `data-colors.category-5` | `Color.TAWN.Light.05` | `data-colors.category-5` | `Color.TAWN.Dark.05` |
| `dataColors[^5]` | Root | `data-colors.category-6` | `Color.TAWN.Light.06` | `data-colors.category-6` | `Color.TAWN.Dark.06` |
| `dataColors[^6]` | Root | `data-colors.category-7` | `Color.TAWN.Light.07` | `data-colors.category-7` | `Color.TAWN.Dark.07` |
| `dataColors[^7]` | Root | `data-colors.category-8` | `Color.TAWN.Light.08` | `data-colors.category-8` | `Color.TAWN.Dark.08` |
| `background` | Root | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| `foreground` | Root | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `secondaryBackground` | Root | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| `tableAccent` | Root | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| `firstLevelElements` | Root | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `secondLevelElements` | Root | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| `thirdLevelElements` | Root | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| `fourthLevelElements` | Root | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| `good` | Root | `text-success` | `Color.Success.700` | `text-success` | `Color.Success.300` |
| `bad` | Root | `text-error` | `Color.Error.700` | `text-error` | `Color.Error.300` |
| `neutral` | Root | `text-disabled` | `Color.Neutral.400` | `text-disabled` | `Color.Neutral.500` |
| `maximum` | Root | `text-brand-solid` | `Color.Brand.500` | `text-brand` | `Color.Brand.400` |
| `minimum` | Root | `background-warning` | `Color.Warning.50` | `background-warning` | `Color.Warning.900` |
| `center` | Root | `text-warning` | `Color.Warning.700` | `text-warning` | `Color.Warning.300` |


***

### **2. textClasses**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `textClasses.callout.fontSize` | textClasses → callout | — | `45` (fixed value) | — | `45` (fixed value) |
| `textClasses.callout.fontFace` | textClasses → callout | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `textClasses.callout.color` | textClasses → callout | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `textClasses.title.fontSize` | textClasses → title | — | `12` (fixed value) | — | `12` (fixed value) |
| `textClasses.title.fontFace` | textClasses → title | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `textClasses.title.color` | textClasses → title | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `textClasses.header.fontSize` | textClasses → header | — | `12` (fixed value) | — | `12` (fixed value) |
| `textClasses.header.fontFace` | textClasses → header | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `textClasses.header.color` | textClasses → header | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `textClasses.label.fontSize` | textClasses → label | — | `10` (fixed value) | — | `10` (fixed value) |
| `textClasses.label.fontFace` | textClasses → label | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `textClasses.label.color` | textClasses → label | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |


***

### **3. visualStyles → * (Global Visuals)**

#### **3.1 visualStyles.*.*.background**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.background[^0].color` | visualStyles → * → * → background | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| `visualStyles.*.*.background[^0].transparency` | visualStyles → * → * → background | — | `0` (fixed value) | — | `0` (fixed value) |

#### **3.2 visualStyles.*.*.border**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.border[^0].color` | visualStyles → * → * → border | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| `visualStyles.*.*.border[^0].show` | visualStyles → * → * → border | — | `true` (fixed) | — | `true` (fixed) |
| `visualStyles.*.*.border[^0].width` | visualStyles → * → * → border | — | `0.5` (fixed) | — | `0.5` (fixed) |

#### **3.3 visualStyles.*.*.categoryAxis**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.categoryAxis[^0].labelColor` | visualStyles → * → * → categoryAxis | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| `visualStyles.*.*.categoryAxis[^0].fontFamily` | visualStyles → * → * → categoryAxis | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `visualStyles.*.*.categoryAxis[^0].showAxisTitle` | visualStyles → * → * → categoryAxis | — | `false` (fixed) | — | `false` (fixed) |

#### **3.4 visualStyles.*.*.valueAxis**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.valueAxis[^0].gridlineColor` | visualStyles → * → * → valueAxis | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| `visualStyles.*.*.valueAxis[^0].labelColor` | visualStyles → * → * → valueAxis | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| `visualStyles.*.*.valueAxis[^0].fontFamily` | visualStyles → * → * → valueAxis | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `visualStyles.*.*.valueAxis[^0].gridlineStyle` | visualStyles → * → * → valueAxis | — | `dotted` (fixed) | — | `dotted` (fixed) |
| `visualStyles.*.*.valueAxis[^0].gridlineThickness` | visualStyles → * → * → valueAxis | — | `1` (fixed) | — | `1` (fixed) |

#### **3.5 visualStyles.*.*.legend**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.legend[^0].fontColor` | visualStyles → * → * → legend | `text-tertiary` | `Color.Neutral.600` | `text-tertiary` | `Color.Neutral.400` |
| `visualStyles.*.*.legend[^0].fontFamily` | visualStyles → * → * → legend | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `visualStyles.*.*.legend[^0].fontSize` | visualStyles → * → * → legend | — | `7` (fixed) | — | `7` (fixed) |

#### **3.6 visualStyles.*.*.title**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.title[^0].fontColor` | visualStyles → * → * → title | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.*.*.title[^0].fontFamily` | visualStyles → * → * → title | `font-family-secondary` | `Font.Family.Secondary` | `font-family-secondary` | `Font.Family.Secondary` |
| `visualStyles.*.*.title[^0].fontSize` | visualStyles → * → * → title | — | `14` (fixed) | — | `14` (fixed) |
| `visualStyles.*.*.title[^0].bold` | visualStyles → * → * → title | — | `true` (fixed) | — | `true` (fixed) |

#### **3.7 visualStyles.*.*.dropShadow**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.*.*.dropShadow[^0].color` | visualStyles → * → * → dropShadow | `black-solid` | `Color.Neutral.Dark Navy` | `black-solid` | `Pure Black` |
| `visualStyles.*.*.dropShadow[^0].transparency` | visualStyles → * → * → dropShadow | — | `70` (fixed) | — | `50` (fixed) |


***

### **4. visualStyles → page**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.page.*.background[^0].color` | visualStyles → page → * → background | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| `visualStyles.page.*.outspacePane[^0].backgroundColor` | visualStyles → page → * → outspacePane | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| `visualStyles.page.*.outspacePane[^0].foregroundColor` | visualStyles → page → * → outspacePane | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.page.*.filterCard[^0].backgroundColor` | visualStyles → page → * → filterCard | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| `visualStyles.page.*.filterCard[^0].foregroundColor` | visualStyles → page → * → filterCard | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.page.*.filterCard[^0].inputBoxColor` | visualStyles → page → * → filterCard | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.800` |


***

### **5. visualStyles → cardVisual**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.cardVisual.*.accentBar[^0].color` | visualStyles → cardVisual → * → accentBar | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| `visualStyles.cardVisual.*.border[^0].color` | visualStyles → cardVisual → * → border | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.800` |
| `visualStyles.cardVisual.*.divider[^0].dividerColor` | visualStyles → cardVisual → * → divider | `border-secondary` | `Color.Neutral.200` | `border-secondary` | `Color.Neutral.700` |
| `visualStyles.cardVisual.*.label[^0].fontColor` | visualStyles → cardVisual → * → label | `text-secondary` | `Color.Neutral.700` | `text-secondary` | `Color.Neutral.300` |
| `visualStyles.cardVisual.*.value[^0].fontColor` | visualStyles → cardVisual → * → value | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.cardVisual.*.title[^0].fontColor` | visualStyles → cardVisual → * → title | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.cardVisual.*.title[^0].background` | visualStyles → cardVisual → * → title | `background-secondary` | `Color.Neutral.25` | `background-secondary` | `Color.Neutral.Dark Navy` |
| `visualStyles.cardVisual.*.referenceLabel[^0].backgroundColor` | visualStyles → cardVisual → * → referenceLabel | `background-brand` | `Color.Brand.500` @ 7.5% | `background-brand` | `Color.Brand.500` @ 15% |


***

### **6. visualStyles → tableEx**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.tableEx.*.columnHeaders[^0].backColor` | visualStyles → tableEx → * → columnHeaders | `background-brand` | `Color.Brand.50` | `background-secondary` | `Color.Neutral.800` |
| `visualStyles.tableEx.*.columnHeaders[^0].fontColor` | visualStyles → tableEx → * → columnHeaders | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.tableEx.*.grid[^0].outlineColor` | visualStyles → tableEx → * → grid | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.700` |
| `visualStyles.tableEx.*.values[^0].fontColor` | visualStyles → tableEx → * → values | `text-primary` | `Color.Neutral.900` | `text-secondary` | `Color.Neutral.300` |
| `visualStyles.tableEx.*.values[^0].backColorSecondary` | visualStyles → tableEx → * → values | `background-primary` | `Color.Neutral.white` | `background-secondary` | `Color.Neutral.800` |


***

### **7. visualStyles → slicer**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.slicer.*.items[^0].background` | visualStyles → slicer → * → items | `background-secondary` | `Color.Neutral.25` | `background-primary` | `Color.Neutral.900` |
| `visualStyles.slicer.*.items[^0].fontColor` | visualStyles → slicer → * → items | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |
| `visualStyles.slicer.*.slider[^0].color` | visualStyles → slicer → * → slider | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |
| `visualStyles.slicer.*.slider[^0].handleFillColor` | visualStyles → slicer → * → slider | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| `visualStyles.slicer.*.slider[^0].handleBorderColor` | visualStyles → slicer → * → slider | `text-brand-solid` | `Color.Brand.500` | `text-brand-solid` | `Color.Brand.500` |


***

### **8. visualStyles → actionButton**

| JSON Property | Hierarchy Level | Alias Token (Light) | Option Token (Light) | Alias Token (Dark) | Option Token (Dark) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `visualStyles.actionButton.*.border[^0].color` | visualStyles → actionButton → * → border | `border-tertiary` | `Color.Neutral.100` | `border-tertiary` | `Color.Neutral.700` |
| `visualStyles.actionButton.*.fill[^0][$id=default].fillColor` | visualStyles → actionButton → * → fill → default | `background-primary` | `Color.Neutral.white` | `background-primary` | `Color.Neutral.900` |
| `visualStyles.actionButton.*.fill[^0][$id=selected].fillColor` | visualStyles → actionButton → * → fill → selected | `background-brand` | `Color.Brand.500` @ 25% | `background-brand` | `Color.Brand.500` @ 25% |
| `visualStyles.actionButton.*.text[^0].fontColor` | visualStyles → actionButton → * → text | `text-primary` | `Color.Neutral.900` | `text-primary` | `Color.Neutral.white` |


***

This hierarchical structure follows the exact JSON theme file order and shows the complete path from root to nested properties with their corresponding design tokens for both light and dark modes.
