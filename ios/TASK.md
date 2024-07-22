## Task
add a filter to the product list that opens in a sheet where you can filter between different color-styles.

the data should be fetched via async await from a given backend

### Hints
ignore force unwraps, tests & error handling


### example
<img src="https://raw.githubusercontent.com/aacml/Recruiting/ios/ios/sheet.gif" width="200" />

---

## Starting code
### ProductStyle.swift
```swift
enum ProductStyle {
    case grey, color, all
}
```

---

### ProductServiceProtocol
```swift
func getProductList(style: ProductStyle) async -> [Product]
```
---

### Backendurls
#### https://raw.githubusercontent.com/aacml/Recruiting/ios/ios/products/all
#### https://raw.githubusercontent.com/aacml/Recruiting/ios/ios/products/grey
#### https://raw.githubusercontent.com/aacml/Recruiting/ios/ios/products/color


## Helpful snippet
```swift
.presentationDetents([.medium])
.presentationDragIndicator(.visible)
```
