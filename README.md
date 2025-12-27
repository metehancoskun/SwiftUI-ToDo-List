# TodoList - SwiftUI Todo List App

Yapılacaklar listesi uygulaması.

## Özellikler

- ✅ Yapılacaklar ekleme
- ✅ Yapılacakları tamamlandı olarak işaretleme
- ✅ Yapılacakları silme
- ✅ Yapılacakları sıralama
- ✅ Verilerin kalıcı saklanması (UserDefaults)



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


