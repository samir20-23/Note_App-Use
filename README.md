

### 1. **Color Utilities**:
   - **Text Color**:
     ```html
     <p class="text-primary">This is a primary text color.</p>
     <p class="text-success">This is a success text color.</p>
     <p class="text-danger">This is a danger text color.</p>
     ```
   - **Background Color**:
     ```html
     <div class="bg-primary">This has a primary background color.</div>
     <div class="bg-success">This has a success background color.</div>
     <div class="bg-danger">This has a danger background color.</div>
     ```

### 2. **Border Utilities**:
   - **Border Color**:
     ```html
     <div class="border border-primary">This has a primary border color.</div>
     <div class="border border-success">This has a success border color.</div>
     ```
   - **Border Style**:
     ```html
     <div class="border border-2">This has a 2px border.</div>
     <div class="border border-dashed">This has a dashed border.</div>
     <div class="border border-solid">This has a solid border.</div>
     ```

### 3. **Flexbox Utilities**:
   - **Flexbox Layout**:
     ```html
     <div class="d-flex">
         <div class="p-2">Item 1</div>
         <div class="p-2">Item 2</div>
         <div class="p-2">Item 3</div>
     </div>
     ```
   - **Justify Content** (Align items horizontally):
     ```html
     <div class="d-flex justify-content-start">Start aligned</div>
     <div class="d-flex justify-content-center">Centered</div>
     <div class="d-flex justify-content-end">End aligned</div>
     <div class="d-flex justify-content-between">Space between</div>
     ```
   - **Align Items** (Align items vertically):
     ```html
     <div class="d-flex align-items-start">Top aligned</div>
     <div class="d-flex align-items-center">Center aligned</div>
     <div class="d-flex align-items-end">Bottom aligned</div>
     ```
   - **Flex Direction** (Control the direction of flex items):
     ```html
     <div class="d-flex flex-row">Row direction (default)</div>
     <div class="d-flex flex-column">Column direction</div>
     ```

### 4. **Width and Height**:
   - **Width**:
     ```html
     <div class="w-25">Width 25%</div>
     <div class="w-50">Width 50%</div>
     <div class="w-75">Width 75%</div>
     <div class="w-100">Width 100%</div>
     ```
   - **Height**:
     ```html
     <div class="h-25">Height 25%</div>
     <div class="h-50">Height 50%</div>
     <div class="h-75">Height 75%</div>
     <div class="h-100">Height 100%</div>
     ```

### 5. **Margin and Padding**:
   - **Margin**:
     ```html
     <div class="m-3">Margin all sides</div>
     <div class="mt-3">Margin top</div>
     <div class="mb-3">Margin bottom</div>
     <div class="ml-3">Margin left</div>
     <div class="mr-3">Margin right</div>
     ```
   - **Padding**:
     ```html
     <div class="p-3">Padding all sides</div>
     <div class="pt-3">Padding top</div>
     <div class="pb-3">Padding bottom</div>
     <div class="pl-3">Padding left</div>
     <div class="pr-3">Padding right</div>
     ```

### 6. **Display Utilities**:
   - **Display Flex**:
     ```html
     <div class="d-flex">Flexbox container</div>
     ```
   - **Display Block**:
     ```html
     <div class="d-block">Block-level element</div>
     ```
   - **Display Inline**:
     ```html
     <span class="d-inline">Inline element</span>
     ```
   - **Display None**:
     ```html
     <div class="d-none">This is hidden</div>
     ```

### Example:

```html
<div class="bg-success text-white p-3 mb-3 d-flex justify-content-between align-items-center">
    <span>Success Message</span>
    <button class="btn btn-danger">Close</button>
</div>
```

### Summary:
- **Colors**: `text-*`, `bg-*`, `border-*`
- **Spacing**: `m-*`, `p-*`, `mt-*`, `mb-*`, `ml-*`, `mr-*`
- **Flexbox**: `d-flex`, `justify-content-*`, `align-items-*`, `flex-*`
 
