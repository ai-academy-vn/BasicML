# Cài đặt môi trường và thư viện cho Machine Learning

# Python

**Python** là ngôn ngữ lập trình rất phổ biến trong cả môi trường học thuật và công nghiệp. Theo số liệu từ IEEE Spectrum, Python đã đứng hạng nhất trên bảng xếp hạng những ngôn ngữ phổ biến vào tháng 8/2018. Python được thiết kế hướng đến việc dễ đọc hiểu, gần với ngôn ngữ tự nhiên (tiếng Anh) và sử dụng nhóm các từ vựng toán học.

Có lẽ Python là ngôn ngữ lập trình dễ tiếp cận nhất. Một lập trình viên với nền tảng cơ bản có thể "master" và bắt đầu bắt tay vào thực hiện một dự án nho nhỏ chỉ sau vài ngày tìm hiểu, thực hành với Python. Điều này thật sự rất có ý nghĩa, đặc biệt là đối với người làm trong môi trường học thuật bởi không cần tốn quá nhiều công sức cho việc tìm hiểu ngôn ngữ, môi trường phát triển, để dành năng lượng vào việc giải quyết các vấn đề nghiên cứu.

Mặc dù đơn giản, dễ tiếp cận, Python đồng thời cũng vô cùng mạnh mẽ, hỗ trợ cả lập trình thủ tục, lập trình hàm và (tất nhiên) lập trình hướng đối tượng.

Python làm việc trên hầu như mọi nền tảng: Windows, Mac, Linux, Raspberry, etc

Hiện nay tồn tại song song hai phiên bản là Python2 và Python3, trong đó Python2 đã không còn được hỗ trợ cập nhật thêm mới bất cứ thứ gì ngoài các gói security updates. Mặc dù vậy, Python2 vẫn được sử dụng khá phổ biến.

Các gói thư viện cho Python có thể được dễ dàng cài đặt và quản lý bởi công cụ PIP (pip installs packages)

## Cài đặt Python

Khi không bị ràng buộc bởi các dự án cũ, phát triển bởi Python2 thì bản Python3 được khuyến nghị sử dụng. Có hai lựa chọn cài đặt Python: Cài đặt từ bản phân phối chính thức từ python.org/downloads; Hoặc cài đặt thông qua Anaconda.

### Cài đặt Python từ python.org
Tải bộ cài đặt tại [python.org/downloads](python.org/downloads) 

![enter image description here](https://lh3.googleusercontent.com/bgRQnf6OmFrg_dKnVl0kZ4r_naQty5C0-6aHbQX1LDQDUArm_3RXF90DMuohJ-np_ua8WaFkY_8F)

Lựa chọn bản cài đặt phù hợp với nền tảng sử dụng (Windows, Mac, Linux, etc). Bài viết này hướng dẫn cài đặt Python 3.7.0 trên môi trường Windows.

Sau khi download bộ cài, thực hiện cài đặt Python trên Windows như sau:

![enter image description here](https://lh3.googleusercontent.com/OpbrHb9A15AhB-FGYu33vtcne563jYpLJn7RYkXRcOVx6CkmkUJT0oUT0NfVdjbtn9IAgANkelyS)

Đánh dấu chọn mục "Add Python 3.7 to PATH" để trình cài đặt tự động thêm đường dẫn của Python vào biến môi trường, sau đó nhấp "Install Now"

### Cài đặt Python thông qua Anaconda

Anaconda là một bản phát hành Python dành cho các ứng dụng liên quan đến khoa học dữ liệu và máy học, với mục đích đơn giản hóa việc quản lý gói thư viện và triển khai ứng dụng. Phiên bản gói thư viện được quản lý bởi Package Management System **conda**

Anaconda đồng thời cung cấp tính năng tạo các môi trường ảo hoàn toàn độc lập với nhau và độc lập với môi trường Python của hệ điều hành nếu được cài sẵn hoặc cài đặt từ bản phân phối chính thức

Bản phân phối Anaconda cũng được đóng gói sẵn hơn 250 gói thư viện thông dụng dành cho khoa học dữ liệu, phù hợp cho Windows, MacOS, Linux
Bước đầu tiên, tải Anaconda tại https://www.anaconda.com/download/

![enter image description here](https://lh3.googleusercontent.com/Ax7UTT3jAflUu4SYXF8lu1-9ijcVrHtSiMgTNTzJ8bys5BACD2ik-KupuT4RP4HIZidQOPS3fNnT)

Lưu ý tải đúng bản cho nền tảng đang sử dụng. Bài viết này hướng dẫn cài đặt trên Windows, bản phân phối Python 3.6, 64-bit.

Sau khi tải bản cài đặt, thực hiện cài đặt theo các bước sau:

![enter image description here](https://lh3.googleusercontent.com/F72HSgOowJn-HZ_hhuK8lR25scShn2ZOULF5e3izULGjrI_Fld7hKrvmZW4vukJtdN_N8KfIWHqV)

Nhấp **Next >** **I Agree**

![enter image description here](https://lh3.googleusercontent.com/VJRtFWIvIuww8WGxkUFTgiYkGckkvtgpCRHCvC5_4N6FNx4A9M2DRodrcEcM1zTsqoOWPGEige4C)

Chọn "Install for: All Users", nhấp **Next >**, tiếp tục nhấp **Next >** cho đến bước sau:

![enter image description here](https://lh3.googleusercontent.com/JrF0MsRPvb0tl489X81TwwuB2BXunUZ9ZI5C6CaqtE_uIf7iBANt4r2aLmKmLQ6rDrrfZ-rOG0vt)

Đánh dấu chọn cả 2 mục thuộc **Advanced Options** như hình minh họa, nhấp **Install**
Sau khi kết thúc cài đặt, để kiểm tra việc cài đặt có thành công hay không, chạy command line (cmd.exe) và gõ thử lệnh 

    > conda
Nếu cài đặt thành công, command line sẽ hiển thị như sau:

![enter image description here](https://lh3.googleusercontent.com/FuHpJlAQwr4i0AQEEPd8iQv5nDM8Kl1AIk6RAGxL7pRqGMaapIq8r7dNI314i9IGatKyvc9lUTjX)

Để kiểm tra việc cài đặt Python, từ trình Command Line, gõ lệnh:

    > python
    
Command line sẽ có các thông tin như sau:

![enter image description here](https://lh3.googleusercontent.com/-SjXw6UwXWFJ8SpyrcThn1MGr3uz7U8qezZhts1flz9kzRVA-cx3pfwarOxk8KhozyF_2aYdATEo)

# Cài đặt thư viện cho Machine Learning
Các thư viện dành cho khoa học dữ liệu, máy học cơ bản gồm NumPy, Scikit-Learn, Matplotlib, Tensorflow, Keras, etc. Trong trường hợp cài đặt Python từ bản phân phối Anaconda, các thư viện kể trên đã được đóng gói sẵn, không cần cài đặt riêng lẻ. Nếu là Python từ bản phân phối chính thức từ Python.Org, cần cài đặt các gói riêng lẻ bằng công cụ PIP

## NumPy

NumPy là gói thư viện cơ bản dành cho khoa học máy tính trên Python, được thiết kế để xử lý dữ liệu dạng mảng, ma trận. Việc xử lý, tính toán dữ liệu dạng mảng với kích thước lớn, nhiều chiều, số lượng bản ghi tùy ý trên NumPy hết sức hiệu quả mà không phải hy sinh quá nhiều về tốc độ so với mảng nhiều chiều kích thước nhỏ. NumPy bao gồm các thành phần:

 - N-dimensional array object
 - Các hàm tính toán phức tạp
 - Các thuật toán thuộc Linear Algebra, Fourier Transform
 - Bộ sinh số giả ngẫu nhiên với đầy đủ các phương pháp, các tùy chọn 

NumPy đóng vai trò quan trọng trong khoa học máy tính. Rất nhiều các thư viện khác được xây dựng bên trên NumPy, sử dụng kiểu dữ liệu mảng nhiều chiều của NumPy như là định dạng dữ liệu chuẩn. Các hàm, các phương thức làm việc với ma trận của NumPy rất ngắn gọn, tiện lợi và hiệu năng cao.

Để cài đặt NumPy sử dụng PIP, thực hiện lệnh sau trên command line (hoặc terminal trên môi trường linux, macos):

    > pip install numpy
    
Hoặc sử dụng công cụ quản lý packages conda:

    > conda install numpy
    
 Điểm cần lưu ý, một số thư viện được xây dựng bên trên thư viện NumPy đòi hỏi phiên bản NumPy dựa trên thư viện MKL (math kernel library - thư viện tối ưu tính toán được phát triển bởi Intel). Trong trường hợp đó, cần phải cài đặt gói *numpy-mkl* bằng cách sau:
 
 - Chọn và download file đóng gói thư viện *whl* phù hợp với phiên bản Python, môi trường hệ thống, kiến trúc 32bit hay 64bit từ https://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy
 - Từ cmd di chuyển đến thư mục có chứa file *whl* đã tải về
 - Nhập lệnh: `> pip install numpy‑1.15.0+mkl‑cp37‑cp37m‑win_amd64.whl` (giả sử file whl đã download có tên như vậy - phù hợp cho Python 3.7, môi trường Windows 64bit)

## Matplotlib

Đây là gói thư viện vô cùng hiệu quả để vẽ đồ thị 2D cho Data Visualization. Matplotlib bao gồm rất phong phú các dạng đồ thị. Người dùng có thể dễ dàng tạo plots, histograms, power spectra, bar charts, errorcharts, scatterplots, etc.. với chỉ vài dòng code.

Matplotlib được tích hợp rất nhiều plug-ins hữu ích, đặc biệt là mplot3d cho vẽ đồ thị 3D
Để cài đặt Matplotlib cho Python, trên *cmd* nhập lệnh:

    > pip install matplotlib

## Scikit-Learn

Scikit-Learn là thư viện cho các ứng dụng máy học rất nổi tiếng, mã nguồn mở và được cấp phép cho môi trường phát triển ứng dụng doanh nghiệp. Scikit-Learn được xây dựng bên trên NumPy, Scipy, và Matplotlib. Thư viện này là một công cụ hết sức hiệu quả cho các bài toán khai phá dữ liệu và phân tích dữ liệu, với đầy đủ các thuật toán máy học được cài đặt sẵn.
Để cài đặt Scikit-Learn sử dụng công cụ PIP, nhập lệnh sau trên cmd:

    > pip install scikit-learn

## Tensorflow

Tensorflow là thư viện vô cùng nổi tiếng, được phát triển bởi Google Brain. Mới đầu Tensorflow chỉ được sử dụng nội bộ bên trong Google. Cho đến tháng 11 năm 2015, Tensorflow được phát hành dưới giấy phép mã nguồn mở Apache 2.0. Từ đó đến nay, thư viện này phát triển một cách thần tốc, trở thành thư viện cho Machine Learning, Deep Learning hàng đầu. Tensorflow được ứng dụng trong cả nghiên cứu lẫn phát triển ứng dụng.

Việc cài đặt các kỹ thuật Deep Learning trở lên hết sức thuận tiện bởi Tensorflow cung cấp các Python API dễ sử dụng.

Tensorflow hiện nay đã hỗ trợ hầu như đầy đủ các nền tảng, kể cả Mobiles, Raspberry, Browsers (với tensorflow.js).

Để cài đặt Tensorflow, từ *cmd* nhập lệnh:

    > pip install tensorflow
    
Đối với máy tính có tích hợp GPU của NVIDIA, cần cài đặt bản built sẵn hỗ trợ GPU để tăng tốc độ tính toán (lên nhiều lần), bằng lệnh:

    > pip install tensorflow-gpu
    
Các cách kể trên sẽ cài đặt thư viện Tensorflow dựa trên bản phân phối chuẩn, được built sẵn với tiêu chí phù hợp với đa số các thiết bị. Vì vậy nó có thể không tối ưu cho một thiết bị nhất định. Ví dụ bản build tiêu chuẩn không hỗ trợ công nghệ AVX, FMA, SSE. Vì vậy với máy tính có CPU hỗ trợ các công nghệ kể trên, cần phải có bản built phù hợp để khai thác tối đa khả năng tính toán (với AVX2, SSE 4.2 hiệu năng tính toán có thể cải thiện đến 3 lần). Trong trường hợp này, cần thực hiện build Tensorflow với các tùy chọn tối ưu cho thiết bị, nhưng đó không phải là việc đơn giản với tất cả mọi người. May mắn là trên Internet có sẵn một kho chứa gần như tất cả các bản built sẵn với các tùy chọn khác nhau và được cập nhật thường xuyên cùng với phiên bản mới phát hành của Tensorflow: https://github.com/lakshayg/tensorflow-build. Để cài đặt, trước tiên cần download file đóng gói *whl* phù hợp với môi trường hệ thống, đặc điểm phần cứng, phiên bản Python trên máy, phiên bản Tensorflow, etc.. Sau khi tải về, từ *cmd* di chuyển đến thư mục chứa file *whl* và nhập lệnh:

    > pip install tensorflow-1.9.0-cp36-cp36m-macosx_10_13_x86_64.whl
    
Với giả thiết cài đặt Tensorflow phiên bản 1.9.0 trên MacOS với phiên bản Python 3.6.
Một điều lưu ý là Tensorflow hiện không hỗ trợ build trên môi trường Windows. Vì vậy chỉ có thể cài đặt Tensorflow bằng bản phân phối chuẩn thông thường.

Sau khi cài đặt Tensorflow, để chắc chắn quá trình cài đặt là thành công có thể kiểm tra bằng cách thực hiện chạy một đoạn script Python trên *cmd* như sau:

- Với bản build cho CPU: 

`> python`

    >> import tensorflow as tf
    >> hello = tf.constant("Hello, Tensorflow")
    >> sess = tf.Session()
    >> print(sess.run(hello))
    
Nếu kết quả được in ra:

    Hello, Tensorflow
    
thì việc cài đặt đã thành công.

- Với bản build cho GPU: 

`> python`

    >> import tensorflow as tf
    >> sess = tf.Session(config=tf.ConfigProto(log_device_placement=True))
    
Nếu quá trình cài tensorflow-gpu thành công, màn hình *cmd* sẽ hiển thị thông tin thiết bị tương tụ như sau:

![enter image description here](https://lh3.googleusercontent.com/VE3q82dPKsKRJOFI8zY_xEemb-vV5Bt3V5uXzaHDP2nEBlJLiaOtQdikCxE4XlpxMsc4EwaqqiSW)

## Keras
Keras được phát triển bởi Francois Chollet, một kỹ sư của Google. Thư viện này được xem như "high-level" API cho deep learning, định nghĩa sẵn gần như toàn bộ các layer thông dụng. Bên dưới nó là phần "low-level" API thuộc thư viện tensorflow, theano hay gần đây là CNTK. Hoặc nói cách khác, Keras như là một **Wrapper** bên ngoài các thư viện machine learning kể trên. Sử dụng Keras giúp cho người dùng xây dựng network hết sức dễ dàng, không cần phải quan tâm đến các khái niệm phức tạp như ***computational graph, session, etc***. Tuy vậy, vì là high-level API, Việc tùy chỉnh các layers hay định nghĩa các hàm mục tiêu phức tạp trên Keras là không dễ dàng.
Trong các phiên bản gần đây, Tensorflow đã tích hợp sẵn Keras trong module **tf.keras** như là một gói API bậc cao của mình. Điều này không những hết sức thuận tiện cho người dùng, mà còn là tiền đề của rất nhiều gói API bậc cao vô cùng hữu dụng của Tensorflow dựa trên nền tảng Keras.
Trong trường hợp sử dụng các phiên bản Tensorflow cũ hoặc dùng backend là các thư viện như Theano hay CNTK, việc cài đặt riêng biệt Keras là cần thiết. Cài đặt sử dụng PIP như sau:

    >pip install keras
Keras mặc định sử dụng Tensorflow làm backend. 
## PyTorch
PyTorch là thư viện machine learning mã nguồn mở được phát triển chủ yếu bởi Facebook AI Research. PyTorch cung cấp hai tính năng nổi bật:

 - Cung cấp các hàm tính toán trên ***Tensor*** (như cách mà numpy tính toán trên ma trận) với khả năng tăng tốc độ dựa trên sử dụng GPU. Khái niệm Tensor trên PyTorch tương đồng với Matrix trên numpy
 - Deep Neural Networks xây dựng trên hệ thống *tape-based autodiff*
 
Điểm nổi bật của PyTorch là khả năng tính toán ngay lập tức (khác biệt với TensorFlow, mặc dù Eager mode mới ra mắt của TF hướng tới khả năng này). Điều này phù hợp với triết lý lập trình trên Python và thuận tiện cho việc debug mã nguồn.

PyTorch cung cấp:

 - API dễ sử dụng
 - Tích hợp mượt mà với Python và các gói thư viện dành cho Data Sciense. PyTorch quá tương đồng với Numpy, đến mức bạn còn không chú ý đến sự khác biệt
 - Graph tính toán động. Thay bằng tính toán dựa trên graph được định nghĩa trước, PyTorch cung cấp khả năng xây dựng và điều chỉnh graph thậm chí trong run-time

Một lợi điểm của PyTorch nữa là khả năng tính toán trên multi GPUs, custom data loader và tiền xử lý dữ liệu.

Cài đặt PyTorch là tương đối dễ dàng cho mọi nền tảng hoặc trên môi trường ảo. Để cài đặt, truy cập vào trang chủ  [PyTorch](https://pytorch.org/), chọn nền tảng sử dụng, sau đó chọn trình quản lý package, phiên bản Python và phiên bản CUDA (trong trường hợp sử dụng GPU).

![enter image description here](https://lh3.googleusercontent.com/08k-cpU2Ju1QaFCAYUzY4Q_kf4n8miW3xiHREk6LH6IVl6UclHfbLhXGeeA2LX9KHwVjZ_J9nFck)

Ví dụ với hình minh họa phía trên để tiến hành cài đặt PyTorch trên Windows, sử dụng trình quản lý package PIP, phiên bản Python 3.6 và CUDA 9.0. Việc còn lại là copy đoạn mã trong "Run this command" và chạy lệnh đã copy trên command line. Cụ thể là:

    pip3 install http://download.pytorch.org/whl/cu90/torch-0.4.1-cp36-cp36m-win_amd64.whl  
    pip3 install torchvision

