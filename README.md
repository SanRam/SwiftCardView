# SwiftCardView
Another working swift card view available in the wild.



**How to use:**
        `yourCard = CardView(width: 200)`

**add uiview to card:**
```
 let headerField = UILabel()
 headerField.text = "To access site features"
 headerField.textAlignment = .center
 headerField.sizeToFit() // make sure you call this to calculate uilabel height.
 yourCard.addArrangedSubview(headerField)
```
![image](https://github.com/SanRam/SwiftCardView/blob/master/cardview.jpeg)

Licence: Free to all.
