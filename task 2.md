# Домашнее задание 2 

## создадим Button (1 branch)
```
var buttonNextScreen  = UIButton()
buttonNextScreen = UIButton(type: .system)
buttonNextScreen.frame = CGRect(x: self.view.frame.width - 100, y: self.view.frame.height - 150, width: 100, height: 30)
buttonNextScreen.setTitle("Screen3", for: .normal)
buttonNextScreen.addTarget(self, action:#selector(screen3), for: .touchUpInside)
self.view.addSubview(buttonNextScreen)

```

## создадим Label (2 branch)

## создадим TextField (3 branch)

## создадим Switch (4 branch)
