# Kien_Thuc_Unity
Di chuyển object trong không gian 2D:
    + can thiệp vào toạ độ:
        - can thiệp thẳng vào transfrom.position += vector ....
        - dùng những hàm viết sẵn của Unity: transform.Translate, Vector2.MoveToward, Vector2.Lerp ...
    + can thiệp vào vật lý:
        - rigibody.velocity: thay đổi trực tiếp vào vận tốc của vật thể
        - rigibody.AddForce: truyền lực cho vật thể và quy vận tốc bởi Unity


    + 3rd party lib: dotween, leantween...

    + Mix giữa toạ độ và vật lý: Rigibody.MovePosition...

Rigibody2D 3 loại Body type:
    - Dynamic: nhận đầy đủ nội lực và ngoại lực

    - Kinematic: bỏ qua ngoại lực, chỉ nhận nội lực 

    - Static: bỏ qua tất

- Physic2D.Gravity: là trọng lực của hệ thống vật lý
- Rigibody2D.Gravity: là độ phóng đại của trọng lực lên 1 vật thể cụ thể


- Update: chạy theo dựa theo frame của máy, mỗi frame là 1 update
- FixedUpdate: chạy theo fixed time step ở trong project setting/time, mặc định là 0.02s
 Time.deltaTime: thời gian giữa 2 frame

 this.transform.position += vector * Time.deltaTime;

 + Bàn phím: - GetKey
             - GetKeyDown
             - GetkeyUp
             - GetButton
             - GetButtonDown
             - GetButtonUp
             - GetAxis
             - GetAxisRaw

+ Chuột: - GetMouse
         - GetMouseDown
         - GetMouseUp

         - mousePosition: Trả về toạ độ của chuột (trên screen World)
            Camera.main.ScreenToWorldPoint(Input.mousePosition);

- Array: O(1)

- List: O(n)

- Stack: fisrt in last out
- Queue: fisrt in first out

Các giải thuật sắp xếp: Selection sort, buble sort, merge sort, heap sort

Delegate function:
    - Action: void callback
    - Func: callback return value
    - Predicate: callback có nhận vào tham số và return boolean

UnityAction/UnityEvent:
    - Sử dụng callback

OOP:
    - trừu tượng: abstract, interface
    - kế thừa: lớp cha, lớp con
    - đa hình: overload, override
    - đóng gói: private, public, protected, internal ... 

SOLID:
 - S: single responsibility principle 
 - O: open/closure principle => Adapter partterm
 - L: Liskove principle 
 - I: Iterface segrement
 - D: Dependency inverstion => Adapter partterm

Các design partterm:
    - Singleton
    - Object pooling
    - Adapter
    - State
    - Observer
    - Command
    - Factory
    - Behavior tree
    - Stratery
    ....

Effects:
    - Line renderer: dòng game draw
    - Trail renderer
    - Light
    - Partical

Coroutine/IEnumorator:
    - Unity main thread
    - 

UI:
    + Canvas: - Screen space - overlay
              - Screen space - Camera
              - World space
    + Anchor/ pivot: master 

Fresher/Interm + -> - Junior + -> - Middle + -> -Senior+ -> quản lý ( expert / team lead )
