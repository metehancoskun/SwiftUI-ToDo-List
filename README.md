# TodoList - SwiftUI Todo List App

Yapılacaklar listesi uygulaması.

## Özellikler

- ✅ Yapılacaklar ekleme
- ✅ Yapılacakları tamamlandı olarak işaretleme
- ✅ Yapılacakları silme
- ✅ Yapılacakları sıralama
- ✅ Verilerin kalıcı saklanması (UserDefaults)

## Ekran Görüntüleri

### GIF Eklemek İçin İki Yöntem:

#### Yöntem 1: Projeye GIF Dosyası Ekleyip Göstermek

1. GIF dosyanızı proje klasörüne ekleyin (örneğin `images/demo.gif`)
2. Aşağıdaki gibi markdown syntax kullanın:

```markdown
![Demo GIF](/Users/metehan/Documents/SwiftUI-Todo-List/images/ToDoList.mov)
```


![Uygulama Tanıtımı](images/ToDoList.gif)


## Örnek Kullanım

```swift
// Yeni bir görev ekle
listViewModel.addItem(title: "Alışveriş yap")

// Görevi tamamlandı olarak işaretle
listViewModel.updateItem(item: selectedItem)
```

## Teknolojiler

- SwiftUI
- MVVM Architecture
- UserDefaults (Veri Saklama)

## Gereksinimler

- iOS 14.0+
- Xcode 12.3+
- Swift 5.0+

