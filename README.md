> ###(Supported platforms)
> - [X] Windows
> - [X] Android
> - [X] Linux
> - [X] IOS
> - [X] HarmonyOS
> ###(Type)
> - [X] Camera
> - [X] Transform
> - [X] Component
> - [X] Object (Unity)
> - [X] LayerMask
> - [X] Rigidbody
> - [x] MonoBehaviour
> - [x] Renderer
> - [x] Mesh
> - [X] Behaviour
> - [X] Physics
> - [X] GameObject
> - [X] Collider
> - [X] Vector4
> - [X] Vector3
> - [X] Vector2
> - [X] Quaternion
> - [X] Bounds
> - [X] Plane
> - [X] Ray
> - [X] Rect
> - [X] Color
> - [X] Matrix4x4
> - [X] Array
> - [x] String
> - [x] Object (C#)
> - [X] Type (C#)
> - [X] List
> - [X] Dictionary
> - [X] Animator
> - [X] CapsuleCollider
> - [X] BoxCollider
> - [X] Time
> - [X] FieldInfo
> - More...

#### (Initialization)
> ``` c++
> Resolve::Init(GetModuleHandle(L"GameAssembly.dll | mono.dll"), UnityResolve::Mode::Mono);
> // Linux or Android
> Resolve::Init(dlopen(L"il2cpp.so | mono.so", RTLD_NOW), UnityResolve::Mode::IL2CPP);
>```
