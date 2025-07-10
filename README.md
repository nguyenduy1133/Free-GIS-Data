# Vietnam GIS Data

This repository provides a collection of free Geographic Information System (GIS) data for Vietnam, focusing on administrative boundaries and key geographical points. The data is available in various formats, primarily **GeoJSON** and **Shapefile (SHP)**, making it compatible with most GIS software and web mapping applications.

-----

# Dữ liệu GIS Việt Nam

Kho lưu trữ này cung cấp bộ sưu tập dữ liệu Hệ thống Thông tin Địa lý (GIS) miễn phí cho Việt Nam, tập trung vào ranh giới hành chính và các điểm địa lý quan trọng. Dữ liệu có sẵn ở nhiều định dạng khác nhau, chủ yếu là **GeoJSON** và **Shapefile (SHP)**, giúp tương thích với hầu hết các phần mềm GIS và ứng dụng bản đồ web.

-----

## Data Categories / Các hạng mục dữ liệu

### 1\. Vietnam Administrative Divisions (Pre-2025) / Đơn vị hành chính Việt Nam (Trước 2025)

This section offers detailed GIS data reflecting Vietnam's administrative divisions **before the planned restructuring in 2025**, which currently comprises 63 provinces and municipalities.

Phần này cung cấp dữ liệu GIS chi tiết phản ánh các đơn vị hành chính của Việt Nam **trước kế hoạch tái cơ cấu vào năm 2025**, hiện bao gồm 63 tỉnh và thành phố trực thuộc trung ương.

  * **`Provinces_included_Paracel_SpratlyIslands.geojson`**:
      * Detailed administrative boundaries of all 63 provinces and municipalities of Vietnam, including the Paracel (Hoàng Sa) and Spratly (Trường Sa) Archipelagos.
      * Địa giới hành chính chi tiết của tất cả 63 tỉnh, thành phố trực thuộc trung ương của Việt Nam, bao gồm cả Quần đảo Hoàng Sa và Trường Sa.
  * **`Provinces_included_Paracel_SpratlyIslands_combine.geojson`**:
      * Simplified and generalized administrative boundaries of all 63 provinces and municipalities of Vietnam, including the Paracel (Hoàng Sa) and Spratly (Trường Sa) Archipelagos. This version is ideal for applications requiring faster rendering or less detail.
      * Địa giới hành chính đã được khái quát hóa và đơn giản hóa của tất cả 63 tỉnh, thành phố trực thuộc trung ương của Việt Nam, bao gồm cả Quần đảo Hoàng Sa và Trường Sa. Phiên bản này lý tưởng cho các ứng dụng yêu cầu hiển thị nhanh hơn hoặc ít chi tiết hơn.

### 2\. Thu Duc City Data / Dữ liệu Thành phố Thủ Đức

Dedicated GIS data for **Thu Duc City**, a key urban area within Ho Chi Minh City, Vietnam.

Dữ liệu GIS chuyên biệt cho **Thành phố Thủ Đức**, một khu vực đô thị trọng điểm thuộc Thành phố Hồ Chí Minh, Việt Nam.

  * **`ThuDucCity_boundary.geojson`**:
      * The precise administrative boundary of Thu Duc City.
      * Địa giới hành chính chính xác của Thành phố Thủ Đức.
  * **`ThuDucCity_ward.geojson`**:
      * Administrative boundaries of the 34 wards (phường) within Thu Duc City.
      * Địa giới hành chính của 34 phường thuộc Thành phố Thủ Đức.

### 3\. Vietnam Administrative Divisions (Post-2025) / Đơn vị hành chính Việt Nam (Từ 2025)

This section provides forward-looking GIS data based on the **planned administrative restructuring of Vietnam from 2025 onwards**, which aims to consolidate the number of provinces and municipalities to 34.

Phần này cung cấp dữ liệu GIS mang tính dự kiến dựa trên **kế hoạch tái cơ cấu hành chính của Việt Nam từ năm 2025 trở đi**, nhằm hợp nhất số lượng tỉnh và thành phố trực thuộc trung ương xuống còn 34.

  * **`Provinces.geojson`**, **`Provinces.shp`**:
      * Administrative boundaries of the 34 projected provinces and municipalities of Vietnam, including the Paracel (Hoàng Sa) and Spratly (Trường Sa) Archipelagos.
      * Địa giới hành chính của 34 tỉnh, thành phố trực thuộc trung ương dự kiến của Việt Nam, bao gồm cả Quần đảo Hoàng Sa và Trường Sa.
  * **`Provincial_capitals.geojson`**, **`Provincial_capitals.shp`**:
      * Point data representing the locations of the **provincial capitals** (trụ sở cấp tỉnh) for the 34 projected provinces/municipalities of Vietnam.
      * Dữ liệu điểm thể hiện vị trí **trụ sở cấp tỉnh** của 34 tỉnh/thành phố trực thuộc trung ương dự kiến của Việt Nam.
  * **`Commune_headquarters.geojson`**, **`Commune_headquarters.shp`**:
      * Point data representing the locations of the **commune headquarters** (trụ sở cấp xã) for the 3321 projected communes, wards, and townships across Vietnam.
      * Dữ liệu điểm thể hiện vị trí **trụ sở cấp xã** của 3321 xã/phường/thị trấn dự kiến trên khắp Việt Nam.

-----

## Usage / Hướng dẫn sử dụng

You can clone this repository to your local machine:

Bạn có thể sao chép kho lưu trữ này về máy tính cục bộ của mình:

```bash
git clone https://github.com/nguyenduy1133/Free-GIS-Data.git
```

The data files can be directly imported into GIS software like QGIS, ArcGIS, or used in web mapping libraries such as Leaflet, OpenLayers, and Mapbox GL JS.

Các tệp dữ liệu có thể được nhập trực tiếp vào phần mềm GIS như QGIS, ArcGIS, hoặc được sử dụng trong các thư viện bản đồ web như Leaflet, OpenLayers và Mapbox GL JS.

-----

## Copyright and Attribution / Bản quyền và Trích dẫn nguồn

This data is provided free of charge for public use. We kindly request that you **cite this repository** as the source when using or distributing this data in your projects, publications, or applications. Appropriate citation helps acknowledge the effort involved in data compilation and allows others to find the original source.

Dữ liệu này được cung cấp miễn phí cho mục đích sử dụng công cộng. Chúng tôi vui lòng yêu cầu bạn **trích dẫn kho lưu trữ này** làm nguồn khi sử dụng hoặc phân phối dữ liệu này trong các dự án, ấn phẩm hoặc ứng dụng của bạn. Việc trích dẫn phù hợp giúp ghi nhận công sức biên soạn dữ liệu và cho phép người khác tìm thấy nguồn gốc.

### How to Cite / Cách trích dẫn

Below are examples of how you can cite this dataset, depending on the style guide you are following.

Dưới đây là các ví dụ về cách bạn có thể trích dẫn bộ dữ liệu này, tùy thuộc vào hướng dẫn trích dẫn bạn đang tuân theo.

**English (APA Style Example):**
Nguyen Duy Liem. (2025, July 10). *Vietnam GIS Data*. GitHub. Retrieved from [https://github.com/nguyenduy1133/Free-GIS-Data](https://github.com/nguyenduy1133/Free-GIS-Data)

**English (MLA Style Example):**
Nguyen Duy Liem. *Vietnam GIS Data*. GitHub, 10 July 2025, [https://github.com/nguyenduy1133/Free-GIS-Data](https://github.com/nguyenduy1133/Free-GIS-Data).

**Vietnamese (Ví dụ theo phong cách cơ bản):**
Nguyễn Duy Liêm. (2025, 10 tháng 7). *Dữ liệu GIS Việt Nam*. GitHub. Truy cập từ [https://github.com/nguyenduy1133/Free-GIS-Data](https://github.com/nguyenduy1133/Free-GIS-Data)

**Vietnamese (Ví dụ rút gọn):**
Nguyễn Duy Liêm. (2025). *Dữ liệu GIS Việt Nam*. [https://github.com/nguyenduy1133/Free-GIS-Data](https://github.com/nguyenduy1133/Free-GIS-Data)

-----

## Disclaimer / Miễn trừ trách nhiệm

This data is provided "as is" without warranty of any kind, either express or implied, including but not limited to the implied warranties of merchantability and fitness for a particular purpose. While efforts are made to ensure accuracy, the maintainers of this repository do not guarantee the completeness, reliability, or accuracy of the data.

The post-2025 data is based on current official plans and public information available at the time of creation and **may be subject to change** as government policies and administrative decisions evolve. Users are advised to verify the data with official sources for critical applications.

Dữ liệu này được cung cấp "nguyên trạng" mà không có bất kỳ bảo đảm nào, dù rõ ràng hay ngụ ý, bao gồm nhưng không giới hạn ở các bảo đảm về khả năng bán được và sự phù hợp cho một mục đích cụ thể. Mặc dù đã nỗ lực để đảm bảo tính chính xác, những người duy trì kho lưu trữ này không đảm bảo tính đầy đủ, độ tin cậy hoặc tính chính xác của dữ liệu.

Dữ liệu sau năm 2025 được xây dựng dựa trên các kế hoạch chính thức hiện hành và thông tin công khai có sẵn tại thời điểm tạo, và **có thể thay đổi** khi các chính sách của chính phủ và quyết định hành chính phát triển. Người dùng nên xác minh dữ liệu với các nguồn chính thức cho các ứng dụng quan trọng.

-----

## Contributions / Đóng góp

We welcome contributions to improve the accuracy or expand the scope of this dataset. If you find any issues or have suggestions, please open an issue or submit a pull request.

Chúng tôi hoan nghênh các đóng góp để cải thiện độ chính xác hoặc mở rộng phạm vi của bộ dữ liệu này. Nếu bạn tìm thấy bất kỳ vấn đề nào hoặc có đề xuất, vui lòng mở một vấn đề (issue) hoặc gửi một yêu cầu kéo (pull request).
