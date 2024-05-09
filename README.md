Câu 1: Reactjs là gì? Hoạt động như nào?
 + ReactJs là một thư viện Javascript mã nguồn mở phát triển bởi Facebook và cộng đồng các nhà phát triển trên thế giới. Với đặc tính linh hoạt, đơn giản và dễ sử dụng. ReactJS đã trở thành một trong những công nghệ phát triển website được ưa chuộng nhất hiện nay.
 + ReactJS cho phép xây dựng giao diện người dùng (UI) dựa trên các thành phần UI riêng lẻ. Dưới đây là 1 số điểm nổi bật của ReactJS:
   1. Hiệu suất cao: ReactJs sử dụng Virtual DOM để tối ưu hóa hiệu suất của ứng dụng. Virtual DOM cho phép ReactJS cập nhật các thay đổi trên trang web một cách nhanh chóng và hiệu quả hơn so với cách truyền thống, giúp tăng tốc độ và hiệu suất của ứng dụng.
   2. Tái sử dụng: ReactJS cho phép tái sử dụng các thành phần UI, giúp giảm thiểu thời gian và chi phí phát triển. Các thành phần UI có thể được sử dụng lại trong nhiều phần khác nhau của ứng dụng, giúp tăng tính linh hoạt và khả năng mở rộng của ứng dụng.
   3. Quản lý trạng thái dễ dàng: ReactJS giúp quản lý trạng thái của ứng dụng một cách dễ dàng. Sử dụng State và Props, ReactJS cho phép các nhà phát triển quản lý trạng thái của các thành phần UI một cách chính xác và dễ dàng.
   4. Hỗ trợ tốt cho SEO: ReactJS cho phép xây dựng ứng dụng web với khả năng tương thích tốt với SEO. Với sự hỗ trợ của các thư viện như React Helmet, ReactJS cho phép tùy chỉnh và quản lý các phần tử meta và title cho từng trang web.
   5. Hỗ trợ đa nền tảng: ReactJS không chỉ được sử dụng để phát triển các ứng dụng web, mà còn dùng để phát triển các ứng dụng di động với React Native. Sử dụng React Navite các nhà phát triển có thể xây dựng ứng dụng di động cho cả IOS và Android sử dụng cùng 1 mã nguồn
+ Hoạt động của ReactJS.
  1. Components: ReactJs xây dựng giao diện người dùng thông qua các compenents, mỗi component đại diện cho một phần của UI và có thể tái sử dụng.
  2. JSX: JSX là cú pháp mở rộng của Javascript giúp viết markup trong Javascript dễ dàng hơn. JSX cho phép bạn viết HTML trong code Javascript.
  3. Virtual DOM: Thay vì thay đổi trực tiếp DOM của trình duyệt, ReactJS sử dụng Virtual DOM để tối ưu hiệu suất. Khi state và props của component thay đổi. ReactJS sẻ tạo ra một Virtual DOM mới và so sánh nó với Virtual DOM trước đó để xác định những thay đổi cần thiết và chỉ tập trung những phần đó trên DOM thực.
  4. Data Flow: ReactJS sử dụng một chiều dữ liệu (one-way data flow), nghĩa là dữ liệu được truyền từ component cha xuống component con thông qua props.
 
Câu 2: Ưu và nhược điểm của ReactJS?
 + Ưu điểm:
   1. Hiệu suất cao: ReactJS sử dụng Virtual DOM để tối ưu hóa hiệu suất của ứng dụng. Thay thì cập nhật toàn bộ DOM. ReactJS chỉ cập nhật những DOM thực sự cần thiết, giúp giảm tải cho trình duyệt và tăng tốc độ của ứng dụng.
   2. Component-Based: ReactJS sử dụng cấu trúc phát triển dựa trên thành phần, giúp việc phát triển và bảo trì ứng dụng dễ dàng hơn bằng cách tách biệt các phần của ứng dụng thành các thành phần độc lập.
   3. JSX: JSX là một cú phát giúp viết HTML trong Javascript. Điều này giúp làm cho mã nguồn dễ đọc hơn, dễ hiểu hơn, dễ bảo trì hơn.
   4. Hỗ trợ tốt cho SEO: React có khả năng render trên server (Server-Side Rendering - SSR), giúp cho các ứng dụng React có thể tối ưu hóa cho việc tìm kiếm trên các công cụ tìm kiếm.
 + Nhược điểm:
   1. Học ngưỡng ban đầu: Dù ReactJS là một cú pháp gần gũi và dễ hiểu, nhưng nó vẫn đòi hỏi một thời gian đầu để hiểu rõ về khái niêm JSX, Virtual DOM, State, Props...
   2. Quản lý trạng thái: React không đi kèm với một giải pháp quản lý trạng thái nào mặc định. Điều này có thể làm cho việc quản lý trạng thái của ứng dụng phức tạp hơn khi không có một hướng dẫn rõ ràng.
   3. Thư viện hơn là Framework: ReactJS chỉ là một thư viện và không cung cấp một cấu trúc hoàn chỉnh như một framework. Điều này có thể làm cho việc quyết định về cấu trúc dự án và các thư viện phụ trợ phức tạp hơn.
   4. Có thể phức tạp với ứng dụng lớn: Dù ReactJS có thể được sử dụng để xây dựng ứng dụng lớn, nhưng không có một cách tiếp cận chuẩn để quản lý ứng dụng khi chúng trở nên lớn và phức tạp.

Câu 3: Virtual DOM là gì?
 + Virtual DOM (DOM ảo) là một biến thể của cây DOM, được sử dụng trong React và một số thư viện Javascript khác để tối ưu hóa hiệu xuất khi cập nhật giao diện người dùng trên website. 
   Ở mức cơ bản, DOM là cách trình duyệt biểu diễn và tương tác với phần tử HTMl của một trang web. Mỗi khi có sự thay đổi trong dữ liệu hoặc trạng thái của ứng dụng web, DOM phải cập nhật để phản ánh các thay đổi đó. Tuy nhiên, việc cập nhật trực tiếp trên DOM có thể làm chậm hiệu suất của ứng dụng, đặc biệt đối với các ứng dụng web lớn và phức tạp.
   Để giải quyết vấn đề này, React sử dụng cơ chế gọi là Virtual DOM. Virtual DOM là một bản sao của cây DOM được lưu trữ trong bộ nhớ trình duyệt. Khi có sự thay đổi trong dữ liệu hoặc trạng thái của ứng dụng. React sẽ tạo ra một Virtual DOM mới, so sánh với Virtual DOM trước đó và xác định các thay đổi cần được áp dụng vào DOM thực sự.
   Quá trình này giúp giảm thiểu số lần cập nhật trực tiếp lên DOM, thay vào đó chỉ cập nhật các phần tử thực sự cần thiết. Kết quả là tăng hiệu suất và tăng trải nghiệm người dùng.
   Tóm lại. Virtual DOM trong React là một kỹ thuật tối ưu hóa hiệu suất bằng cách sử dụng một bản sao của cấy DOM trong bộ nhớ để giảm thiểu số lần cập nhật trực tiếp lên DOM thực sự.

Câu 4: Single Page Application là gì?
  + Single Page Application (SPA) là một loại ứng dụng web mà các trang không được tại lại hoàn toàn khi người dùng thực hiện các tương tác, như là chuyển đổi giữa các trang hoặc thực hiện các hành động khác. Thay vào đó, toàn bộ hoặc một phần của nội dung của trang được tải bằng Javascript khi cần thiết, thường thông qua AJAX, và sau đó được hiển thị trên cùng 1 trang.
    Điều này có nghĩa là khi người dùng điều hướng giữa các thành phần của ứng dụng, trình duyệt không cần phải tải lại trang hoặc yêu cầu tải trang từ máy chủ. Thay vào đó, các thay đổi được thực hiện mà không làm gián đoạn trải nghiệm người dùng, tạo ra cảm giác mượt và  nhanh  chóng.
    Các ứng dụng Single Page Application thường sử dụng các framework Javascript như React, Angular, Vue.js để quản lý việc tải và hiển thị các nội dung, cũng như quản lý trạng thái của ứng dụng. Các công nghệ như Routing và State Management cũng được sử dụng để điều hướng giữa các "Trang ảo" và quản lý dữ liệu ứng dụng.
    Một số ưu điểm của SPA bao gồm trải nghiệm người dùng tốt hơn, tăng tốc độ tải trang và giảm tải cho máy chủ vì không phải load lại toàn bộ trang. Tuy nhiên, cũng có nhược điểm như việc quản lý bộ nhớ và SEO khó khăn hơn do một số công cụ tìm kiếm không thích ứng với việc index các ứng dung dựa trên Javascript.
   
   
