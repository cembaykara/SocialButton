<h1> SocialButton </h1>

This creates  a custom UIButton with given social network. Depends on <a href = "https://github.com/PureLayout/PureLayout">PureLayout</a>

<p align="center">
<img src="https://github.com/cembaykara/SocialButton/blob/master/screenshot.png?raw=true" width="35%" title="Screenshot">
</p>

<h3>Usage</h3>


```swift
let facebookButton = SocialButton(with: .facebook)
```

you can then;

```swift
facebookButton.addTarget(self, action: #selector(didPressButton), for: .touchUpInside)
```