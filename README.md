# PetStore-.NET
Phần mền quản lý cửa hàng thú cưng trên winform C# .NET - Pet store management software on winform C# .NET

# Thành Viên
| MSSV          | Họ tên                   | Nội Dung Thực Hiện                              |
|---------------|--------------------------|-------------------------------------------------|
| 2001190243    | Đinh Phát Tài            | Thực hiện toàn bộ nội dung đồ án                |

# Giới Thiệu Phần Mền Quản Lý Cửa Hàng Thú Cưng - Introducing Pet Store Management Software
Phần mền quản lý cửa hàng thú cưng - Pet Store Management Software

Hệ thống quản lý cửa hàng mua bán thú cưng còn được biết đến là hàng loạt những công việc được người phụ trách mảng này làm đi làm lại trong một khoảng thời gian dài nhất định. Đó có thể là nhận thú cưng trực tiếp từ khách hàng, hoặc gián tiếp qua email, điện thoại, mạng xã hội (zalo, facebook…),…

Hiện nay, hệ thống quản lý cửa hàng mua bán thú cưng chủ yếu được ứng dụng từ những phần mềm quản lý bán hàng. Điều này, giúp chủ cửa hàng kiểm soát , quản lý lượng hàng hóa một cách chặt chẽ. Việc quản lý của hệ thống sẽ được thể hiện cụ thể qua các khâu: quản lý thú cưng, quản lý kho, quản lý nhân viên, quản lý mua nhập thú cưng,…
Trong thời đại công nghệ phát triển mạnh mẽ như hiện nay, thì các phần mềm quản lý trở thành công cụ hữu ích hơn bao giờ hết cho hoạt động quản lý bán hàng.
Hệ thống quản lý cửa hàng mua bán thú cưng là một phương thức để chủ doanh nghiệp có thể giám sát được hoạt động bán hàng của nhân viên. Đồng thời, xem xét tính trung thực của nhân viên bán hàng

- [x] Các thư viện hỗ trợ trong phần mền
  - [Mã hoá mật khẩu MD5](https://vi.wikipedia.org/wiki/MD5)
  - [Thư viện hỗ trợ Report hoá đơn](https://www.nuget.org/packages/CrystalDecisions.CrystalReports/)
  - [Thông tin xuất Excel](https://docs.microsoft.com/en-us/dotnet/api/microsoft.office.interop.excel?view=excel-pia)

# Chức năng và nghiệp vụ của PetStore
Phần mền quản lý cửa hàng thú cưng - Pet Store Management Software
- [x] Chức năng danh mục
  - Quản lý quyền đăng nhập hệ thống ✓
    - Nội dụng: Chức năng cho phép tài khoản của nhân viên đăng nhập với loại quyền của mình được set trong hệ thống.
  - Quản lý thông tin nhân viên ✓
    - Nội dung: Chức năng cho phép quản lý có thể thêm xoá sửa các nhân viên có trong hệ thống.
  - Quản lý giống, loài thú cưng ✓
    - Nội dung: Chức năng cho phép quản lý có thể thêm xoá sửa các giống và loài của thú cưng được bán trong cửa hàng.
  - Quản lý thông tin khách hàng ✓
    - Nội dung: Chức năng cho phép quản lý hay nhân viên có thể thêm xoá sửa khách hàng khi đến với hệ thống cửa hàng.
  - Quản lý đơn hàng ✓
    - Nội dung: Chức năng cho phép quản lý có thể xem và sửa nội dung của các đơn hàng đã bán.
- [x] Chức năng nghiệp vụ:
  - Chức năng bán thú cưng: ✓
    - Nội dung: Chức năng cho phép nhân viên hay quản lý có thể bán thú cưng cho khách hàng. Hệ thống chỉ lưu đơn hàng lại khi khách hàng thanh toán đơn hàng.
