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

Câu 5: Sự khác nhau giữa Class Component và Function Component? Bạn đang sử dụng dạng nào và tại sao?
 + Cú pháp:
   1. Class Component được định nghĩa bằng cách tạo một lớp Javascript, thường là một subclass của "React.Component".
   2. Function components là các hàm Javascript thông thường trả về JSX.
 + Quản lý trạng thái:
   1. Trong class component bạn có thể sử dụng `this.state` để lưu trữ và quản lý trạng thái của component.
   2. Function component không có trạng thái nội bộ, nhưng bạn có thể sử dụng React Hooks như `useState` để thêm trạng thái cho function component
 + Lifecycle mothods:
   1. Class component có thể sử dụng lifecycle method thư `componentDismount1`, `componentDidUpdate`, và `componentWillUmount` để thực hiện các hành động nhất định trong vòng đời của component.
   2. Function component có thể sử dụng useEffect hook để thực hiện các vụ tương tự như lifecycle methods.
 + Tính linh hoạt và đơn giản:
   1. Function component thường được coi là đơn giản hơn và dễ đọc hơn so với class component. Việc sử dụng hooks trong function component giúp tạo ra code ngắn gọn và dễ hiểu hơn.
 + Tổng kết: Mình đang sử dụng function component vì triển khai code ngắn gọn và dễ hiểu hơn.

Câu 6: Hãy trình bày những giai đoạn có trong lifeCycle của 1 component?
 + LifeCycle của một component trong lập trình phần mềm thường bao gồm các giai đoạn sau:
 1. Khởi tạo (Initialization):
    + Trong giai đoạn này component được khởi tạo. Các biến địa phương được khai báo và cài đặt, các tài nguyên cần thiết được cấp phát, và các trạng thái ban đầu được thiết lập. Điều này thường xảy ra khi một instance mới của component được tạo.
 2. Hiển thị (Mounting):
    + Trong giai đoạn này component được thêm và DOM và cây UI, làm cho nó trở nên hiển thị và có thể tương tác bởi người dùng. Các sự kiện các hàm lắng nghe sự kiện có thể được kích hoạt ở đây.
 3. Cập nhật (Updating):
    + Trong giai đoạn này component có thể cần cập nhật do thay đổi trạng thái hoặc props. React ví dụ sẽ gọi `render()` sau mỗi lần props hoặc state thay đổi. Các lifeCycle methods như `componentDidUpdate()` có thể được gọi trong giai đoạn này.
 4. Hủy bỏ (Unmounting):
    + Khi component không được sử dụng nữa, ví dụ nó bị gỡ bỏ khỏi DOM hoặc cây UI, tài nguyên được giải phóng và các lắng nghe sự kiện được loại bỏ. Trong React `conponentWillUmount` là một ví dụ về một lifeCycle mothed được gọi trong đoạn này

Câu 7: Một componet có thể được "Rerender" lại khi nào?
 Một component có thể được rerender trong các trường hợp sau:
 1. Thay đổi Props: Nếu các props được truyền vào component thay đổi, React sẽ rerender component để áp dụng các thay đổi mới. Điều này đặc biệt quan trọng khi Props được sử dụng để tính toán trạng thái hoặc nội dung của component.
 2. Thay đổi State: Khi trạng thái của component thay đổi bằng cách gọi `setState()` hoặc một hàm tương tự, component sẽ rerender để cập nhật giao diện người dùng theo trạng thái mới.
 3. Kích hoạt từ cha: Nếu commponent được nhận từ props mới từ component cha, hoặc nếu component cha tự rerender, component con sẽ rereder để cập nhật dữ liệu mới
 4. Thay đổi trong context: Nếu component sử dụng context và giá trị trong context thay đổi, component sẽ rerender để áp dụng các giá trị mới từ context.
 5. Gọi hàm `forceUpdate()`: Trong một số trường hợp bạn có thể gọi `forceUpdate()` trên một component để buộc nó rerender mặc dù không có sự thay đổi props hoặc state. Tuy nhiên điều này không được khuyến khích và nên tránh sử dụng nếu có thể,  vì nó có thể sẽ gây ra hiệu suất không hiệu quả và làm mất đi sự tối ưu tự nhiên của React.

Câu 8: JSX là gì? Browser có thể đọc được JSX hay không?
 + JSX là một phần mở rộng của Javascript được sử dụng phổ biến trong React để viết các đoạn mã có cấu trúc gần giống HTML để xây dựng giao diện người dùng. JSX cho phép bạn kết hợp với HTML với Javascript, giúp tạo ra mã ngắn gọn, dễ đọc dễ hiểu hơn so với việc sử dụng các phương thức Javascript truyền thống để tạo ra các thành phần giao diện
 + Browser không thể hiểu trực tiếp JSX, JSX phải được biên dịch thành Javascript thông thường trước khi nó được hiểu bởi trình duyệt. Điều này thường được thực hiện bằng cách sử dụng các công cụ như Babel trong quá trình phát triển ứng dụng React. Babel sẽ biên dịch JSX thành mã Javascript tương ứng trước khi ứng dụng được triển khai lên môi trường sản xuất hoặc khi chạy trên trình duyệt.

Câu 9: Stateless component và statefull component khác nhau thế nào?
 Trong lập trình React sự khác biệt giữa "stateless component" (Component không trạng thái) và "stateful component" (Component có trạng thái) là một khía cạnh quan trọng trong việc hiểu và thiết kế các thành phần trong ứng dụng. Dưới đây là sự khác biệt chính giữa hai loại component này:
 + Stateless Component (Component không trạng thái)
   1. Định nghĩa: Stateless component là những component không quản lý bất kỳ trạng thái nào. Chúng chỉ nhận Props và Render giao diện theo props đó.
   2. Cú pháp:
       Thường được viết dưới dạng hàm (Function components)
      ```
      const Greeting = (props) => {
          return <h1>Hello, {props.name}</h1>;
      }
      ```
    4. Đặc điểm:
       - Không có lifeCycle methods (như componentDidMount, componentDidUpdate)
       - Đơn giản và dễ kiểm tra
       - Hiệu suất tốt hơn trong một số trường hợp vì không cần quản lý trạng thái
    5. Sử dụng:
       - Thích hợp cho các thành phần trình bày đơn giản, nơi không cần quản lý trạng thái hoặc logic phức tạp.
  + Stateful component (Component có trạng thái)
    1. Định nghĩa:
       Stateful component là những component có thể quản lý trạng thái nội bộ (state). Chúng có thể cập nhật và lưu trữ thông tin về trạng thái của chính mình.
    2. Cú pháp:
       Thường được viết dưới dạng (class component) hoặc sử dụng hooks trong function component (Function component with hooks)
       
      // Class component
      ```
      class Greeting extends React.Component {
      constructor(props) {
       super(props);
       this.state = { name: 'John' };
      }
      
      render() {
       return <p>Hello, {this.state.name}!</p>;
      }
      }
      ```
    
      // Function component with hooks
      ```
      import React, { useState } from 'react';
      
      const Greeting = () => {
      const [name, setName] = useState('John');
      return <p>Hello, {name}!</p>;
      };
      ```

    3. Đặc điểm:
       - Có fifeCycle method ( Đối với class component )
       - Có thể quản lý và cập nhật trạng thái nội bộ.
       - Thường phức tạp hơn statless component do cần quản lý trạng thái và logic.
    4. Sử dụng:
       Thích hợp cho các thành phần yêu cầu quản lý trạng thái hoặc có logic phức tạp như form, giao diện người dùng.

    Kết luận:
      + Stateless component rất tốt cho các thành phần đơn giản và chỉ dựa vào dữ liệu props
      + Stateful components phù hợp hơn khi cần quản lý trạng thái logic phức tạp trong component.
   
    Với sự xuất hiện của hooks trong React, sự khác biệt giữa stateless và stateful component đã trở nên mờ nhạt hơn, vì giờ đây chúng ta có thể quản lý trạng thái trong Function component một cách dễ dàng, giúp cho code trở nên sạch và dễ quản lý hơn.

Câu 10: Presentational component và container component khác nhau thế nào?
  Trong lập trình React, khái niệm "Presentational component" (Component trình bày) và "Container component" (Component chứa) là một cách tiếp cận trong việc tổ chức và quản lý mã nguồn theo mô hình phân chia trách nhiệm rõ ràng. Đây là sự khác biệt chính giữa 2 loại component này. 
  + Presentational Component (Component trình bày)
    1. Địng nghĩa: Presentional component chủ yếu tập trung vào việc render giao diện người dùng. Chúng không chứa logic phức tạp không quản lý trạng thái của ứng dụng ( hoặc chỉ quản lý trạng thái liên quan đến giao diện)
    2. Đặc điểm:
       - Nhận dữ liệu và callback functions thông qua props
       - Không có kết nối trực tiếp với store (trong trường hợp sử dụng Redux hoặc các state management khác)
       - Thường là các component không trạng thái (stateless components), những cũng có thể là các stateful component nếu cần quản lý trạng thái liên quan đến giao diện.
       - Dễ kiểm tra vì chúng chỉ liên quan đến giao diện và dữ liệu đầu vào
    3. Ví dụ:
    ```
    const Button = ({ label, onClick }) => {
     return <button onClick={onClick}>{label}</button>;
    };
    ```
 + Container Component (Conponent chứa)
    1. Định nghĩa:
       + Container component chịu trách nhiệm quản ý logic và trạng thái của ứng dụng. Chúng thường kết nối với các nguồn dữ liệu và quyết định dữ liệu nào sẽ được truyền xuống các presentional component
    2. Đặc điểm:
       + Quản lý trạng thái của ứng dụng hoặc kết nối với store (trong redux hoặc các state management khác).
       + Xử lý các tác vụ logic như gọi API, xử lý sự kiện, và quản lý dữ liệu.
       + Thường chứa các presentational components bên trong để render giao diện
    4. Ví dụ:
       ```
          import React, { Component } from 'react';
          import { connect } from 'react-redux';
          import Button from './Button';
          
          class ButtonContainer extends Component {
           handleClick = () => {
           // Logic xử lý khi nút được nhấn
           this.props.dispatch({ type: 'BUTTON_CLICKED' });
           }
           
           render() {
           return <Button label="Click me" onClick={this.handleClick} />;
           }
          }
          
          export default connect()(ButtonContainer);
       ```
 + Sự khác biệt chính
    1. Trách nhiệm:
       - Presentational Components: Tập trung vào việc hiển thị giao diện. Nhận dữ liệu và hành động từ props
       - Container component: Tập trung vào logic và trạng thái của ứng dụng. Kết nối các nguồn dữ liệu và quản lý dữ liệu
    2. Cách sử dụng:
       - Presentational Component: Được sử dụng để tạo ra các phần tử giao diện đơn giản, tái sử dụng được
       - Container Component: Được sử dụng để chứa và quản lý các presentational component, xử lý logic phức tạp và trạng thái
      
 + Lợi ích của việc phân chia
   - Separation of concerns: Giúp tách biệt rõ ràng giữa giao diện và logic, làm cho mã nguồn dễ hiểu và dễ duy trì hơn
   - Tái sử dụng: Presentational component có thể được tái sử dụng ở nhiều nơi trong ứng dụng vì chúng k bị ràng buộc với logic cụ thể.
   - Dễ kiểm tra: Presentational Component dễ dàng kiểm tra hơn vì chúng chỉ phụ thuộc vào props và không chứa logic phức tạp.
  
  Kết luận: Sự phân chia giữa presentational và container component giúp tăng tính cấu trúc và khả năng bảo trì của mã nguồn. Presentational component tập trung vào việc hiển thị giao diện, trong khi container component quản lý logic và trạng thái của ứng dụng.

  Câu 11: Controller component và uncontrolled component khác nhau thế nào?
   Trong React khái niệm controller component ( Thành phần điều khiển ) và uncontrolled component ( Thành phần không điều khiển ) mô tả cách thức quản lý trạng thái của các thành phần đầu vào trong giao diên người dùng. DƯới đây là sự khác biệt giữa chúng.
   + Controller Component (Thành phần điều khiển)
     - Quản lý trạng thái bằng state: Thành phần điều khiển quản lý giá trị của các trường đầu vào thông qua trạng thái (state) của React. Giá trị của trường đầu và được lưu trữ trong state và cập nhật bằng cách sử dụng các sự kiện (event) như `onChange`.
     - Liên kết giá trị và sự kiện: Để thành phần đầu vào ( như `<input>`, `<textarea>`, hoặc `<select>` ) trở thành một component, bạn cần liên kết thuốc tính value của nó với một state của React và sử dụng thuộc tính `onChange` để cập nhật state này khi người dùng thay đổi giá trị đầu vào.
     - Dễ dàng kiểm soát và xác thực dữ liệu: Vì giá trị của các trường đầu vào được lưu trữ trong state, bạn có thể dễ dàng thực hiện các thao tác kiểm soát và xác thực dữ liệu trước khi cho phép người dùng gửi thông tin.
     - Ví dụ:
              ```
                      class ControlledForm extends React.Component {
                        constructor(props) {
                          super(props);
                          this.state = { value: '' };
                      
                          this.handleChange = this.handleChange.bind(this);
                          this.handleSubmit = this.handleSubmit.bind(this);
                        }
                      
                        handleChange(event) {
                          this.setState({ value: event.target.value });
                        }
                      
                        handleSubmit(event) {
                          alert('A name was submitted: ' + this.state.value);
                          event.preventDefault();
                        }
                      
                        render() {
                          return (
                            <form onSubmit={this.handleSubmit}>
                              <label>
                                Name:
                                <input type="text" value={this.state.value} onChange={this.handleChange} />
                              </label>
                              <input type="submit" value="Submit" />
                            </form>
                          );
                        }
                      }
              ```

 + Uncontrolled Component (Thành phần không điều khiển)
   - Quản lý trạng thái bằng DOM: Thành phần không điều khiển không sử dụng state của React để quản lý giá trị của các trường đầu vào. Thay vào đó, giá trị của chúng được quản lý bởi DOM và truy cập qua thông số ref.
   - Truy cập giá trị của ref: Để lấy giá trị của một trường đầu vào không điều khiển, bạn cần sử dụng thuộc tính 'ref' để tham chiếu đến phần tử DOM và truy cập giá trị của nó khi cần thiết.
   - Đơn giản hơn, ít mã hơn: Thành phần không điều khiển thường ít phức tạp hơn vì không cần phải liên kết giá trị và sự kiện. Tuy nhiên, nó khó kiểm soát và xác thực dữ liệu hơn so với thành phần điều khiển
   - Ví dụ:
          ```
          constructor(props) {
           super(props);
           this.input = React.createRef();
          
           this.handleSubmit = this.handleSubmit.bind(this);
          }
          
          handleSubmit(event) {
           alert('A name was submitted: ' + this.input.current.value);
           event.preventDefault();
          }
          
          render() {
           return (
             <form onSubmit={this.handleSubmit}>
               <label>
                 Name:
                 <input type="text" ref={this.input} />
               </label>
               <input type="submit" value="Submit" />
             </form>
           );
          }
          }
          ```

  + Tóm tắt:
    - Controller component: Quản lý giá trị thông qua state của React, dễ dàng kiểm soát và xác thực dữ liệu, những mã nguồn phức tạp hơn
    - Uncontroller component: Quản lý giá trị thông qua DOM và sử dụng ref, ít phức tạp hơn nhưng khó kiểm soát và xác thực dữ liệu hơn.
   
Câu 12: Khi cần hiển thị một list component ra giao diện bạn làm như thế?
 Để hiển thị một danh sách các thành phần (component) trong giao diện React, bạn thường sử dụng phương pháp lặp qua một mảng dữ liệu và tạo các phần tử React tương ứng. Dưới đây là các bước cơ bản để thực hiện điều này:
  1. Chuẩn bị dữ liệu: Bạn cần có một mảng chứ dữ liệu bạn muốn hiển thị. Mỗi phần tử trong mảng này sẽ được sử dụng để tạo một thành phần React.
  2. Sử dụng phương thức `map()`: sử dụng phương thức `map()` để lặp qua mảng dữ liệu và tạo một thành phần React cho mỗi phần tử trong mảng.
  3. Đặt Key cho mỗi thành phần: Mỗi thành phần trong danh sách cần một thuộc tính `Key` duy nhất để React có thể theo dõi và cập nhật hiệu quả các phần tử trong danh sách.
  4. Dưới đây là ví dụ cụ thể:
     Giả sử bạn có một mảng các đối tượng, mỗi đối tượng đại diện cho môt người dùng và bạn muốn hiển thị danh sách các người dùng này:
     ```
         const users = [
          { id: 1, name: 'Alice', age: 25 },
          { id: 2, name: 'Bob', age: 30 },
          { id: 3, name: 'Charlie', age: 35 }
         ];
         
         function UserList() {
          return (
          <ul>
           {users.map(user => (
             <li key={user.id}>
               {user.name} - {user.age} years old
             </li>
           ))}
          </ul>
          );
         }

     ```
     Ví dụ với Component Con: Nếu bạn muốn hiển thị mỗi người dùng dưới dạng một thành phần con (Child component), bạn có thể làm như sau:
      1. Tạo thành phần con: Tạo một thành phần con để hiển thị thông tin người dùng.
      2. Truyền Props cho thành phần con: Truyền dữ liệu từ thành phần cha vào thành phần con thông qua Props
      3. Ví dụ: 
         ```
          // Thành phần con để hiển thị thông tin người dùng
          function User({ user }) {
           return (
           <div>
           <h2>{user.name}</h2>
           <p>Age: {user.age}</p>
           </div>
           );
          }
          
          // Thành phần cha để hiển thị danh sách người dùng
          function UserList() {
           return (
           <div>
           {users.map(user => (
           <User key={user.id} user={user} />
           ))}
           </div>
           );
          }
         ```

     Tổng hợp lại:
      1. Tạo và chuẩn bị dữ liệu: Bạn cần một mảng dữ liệu để lặp qua.
      2. Sử dụng `.map()` để tạo các phần tử React: Lặp qua mảng dữ liệu và tạo thành phần cho mỗi phần tử.
      3. Cung cấp `Key` duy nhất cho mỗi phần tử : Sử dụng thuộc tính `key` để cung cấp một định dạng duy nhất cho mỗi phần tử trong danh sách.
      4. Ví dụ hoàn chỉnh:
         ```
          const users = [
           { id: 1, name: 'Alice', age: 25 },
           { id: 2, name: 'Bob', age: 30 },
           { id: 3, name: 'Charlie', age: 35 }
          ];
          
          function User({ user }) {
           return (
           <div>
           <h2>{user.name}</h2>
           <p>Age: {user.age}</p>
           </div>
           );
          }
          
          function UserList() {
           return (
           <div>
           {users.map(user => (
           <User key={user.id} user={user} />
           ))}
           </div>
           );
          }
          
          export default UserList;
         ```



Câu 13: Tại sao mỗi thành phần trong list phải có key?
  1. Hiệu suất: `Key` giúp React cập nhật danh sách hiệu quả hơn.
  2. Tránh vấn đề về hiển thị: `key` ngăn ngừa các lỗi về hiển thị và trạng thái
  3. Phân biệt phần tử: `key` giúp React nhận diên và theo dõi các phần tử một cách chính xác
     
Câu 14: React Portal là gì? Hãy cho ví dụ ứng dụng React Portal?
 React Portal là một tính năng trong React cho phép bạn render lại các phần tử con vào một DOM node khác nhau nằm ngoài DOM của thành phần cha. Điều nãy hữu ích khi bạn cần render các phần tử nhưng không muốn chúng bị ràng buộc vào vị trí của thành phần cha trong cây DOM
 Portals thường được sử dụng để tạo thành phần giao diện người dùng như modal, tooltip hay các menu dropdows, những thành phần mà cần "Thoát khỏi" sự ràng buộc về bố cục và vị trí của thành phần cha hiện tại.

 Ví dụ ứng dụng Portal

Câu 15: React Hooks là gì? Kể tên những loại hooks mà bạn biết?
Câu 16: Props là gì?
Câu 17: Component con có thể thay đổi trực tiếp giá trị props của component cha không?
Câu 18: Nếu như component cha truyền một props mà component con không sử dụng thì chuyện thì xảy ra?
         
   
