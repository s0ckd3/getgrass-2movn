# Hỗ trợ chạy Grass Lite Extension với nhiều proxy.
Hỗ trợ chạy số lượng lớn extension GetGrass Lite với api proxy (Chỉ hỗ trợ proxy từ webite ipviet.store) và tệp txt

# Hướng dẫn
Để sử dụng bạn cần cài đặt những thông tin cơ bản để sử dụng. Nếu không am hiểu vui lòng không thay thế các giá trị `devicetype`, `version`, `extension_id`, `user_agent`.
```
{
  "username": "", // Email tài khoản
  "password": "",  // Mật khẩu tài khoản
  "proxy_api_key": "", // API của proxy khi mua proxy tại ipviet.store (Dùng proxy từ file text thì bỏ trống)
  "proxy_path": "proxies.txt", // Tên file proxy (Để trong thư mục data)
  "devicetype": "extension", // Bản extension
  "version": "5.1.1", // Phiên bản extension
  "extension_id": "lkbnfiajjmbhnfledhphioinpickokdi", // id extension
  "number_of_turn": 20, Số lượng chạy đồng thời mỗi lượt. (Nếu có nhiều proxy sẽ chia nhỏ ra để chạy lần lượt)
  "time_delay": 10000, delay mỗi lượt chạy
  "user_agent": [ // user_agent cho trình duyệt
    "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36 Edg/131.0.2903.86",
    "Mozilla/5.0 (Windows NT 10.0; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36 Edg/132.0.2903.86",
    "Mozilla/5.0 (Windows NT 10.0; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36 Edg/133.0.2903.86",
    "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36",
    "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/132.0.0.0 Safari/537.36 Edg/132.0.0.0",
    "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36"
  ]
}
```

Cuối cùng bạn chỉ cần chạy app **getgrass-app_v2.exe** cho windown hoặc **getgrass-app_v2** trên linux
