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

```
var label1 = UILabel()
label1.frame = CGRect(x: 0, y: 0, width: 100, height: 30)
label1.center = view.center
label1.text = "TestLabel"
label1.adjustsFontSizeToFitWidth = true
self.view.addSubview(label1)

```

## создадим TextField (3 branch)

```
var textField  = UITextField()
textField = UITextField(frame: CGRect(x: 0, y: 0, width: 300, height: 40))
textField.center = CGPoint(x: view.center.x, y: view.center.y + 100.0)
textField.borderStyle = .roundedRect
textField.placeholder = "enter text"
textField.textAlignment = .center
view.addSubview(textField)// сюда пробуем добавить конфиликт
```

## создадим Switch (4 branch)

```
var sw  = UISwitch()
sw.center = CGPoint(x: coord.midX, y: coord.midY-100)
self.view.addSubview(sw)
sw.addTarget(self, action: #selector(sw(target: )), for: .valueChanged)// в остновную ветку main добавим этот комментарий 
sw.addTarget(self, action: #selector(sw(target: )), for: .valueChanged)// в ветке switch добавляем этот комментарий

```
Добавим доп информацию для выгрузки на github


теперь мы добавим информацию из удаленного репозитория github, для последующей обработки локально
