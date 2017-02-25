### Design Patterns

####Creational
**1. Abtract Factory**: Tạo 1 *Interface | Abstract* để quy định các objects khác.
**2. Factory Method**: Tạo 1 *Object* để khởi tạo các object khác.

####Structural
**1. Decorator**: Dùng để mở rộng method cho một object.

####Behavioral
**1. Strategy**: Tách 1 chức năng dễ thay đổi ra khỏi object. Sau đó tạo 1 tập hợp các thuật toán (Object - cùng 1 interface) để xử lý chắc năng này.
**2. Observer**: Observers-Subject: khi Subject thay đổi thì đồng loạt báo cho tất cả các Observer (*Observer có cùng 1 interface & Observer độc lập với nhau*)
**3. Chain of responsibility**: Observers-Subject: khi Subject thay đổi thì lần lượt báo cho các Observer (*Observer có cùng 1 interface & Observer chứa lẫn nhau: Observer1(Observer2(Observer..(Observer..))*)

