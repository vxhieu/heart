1. Config Allow Multiple Boxes for Shipping có ảnh hưởng gì đến hoạt động của product ngoài frontend hay không?
   - A. Có
   - B. Không.
   - C. Tùy thuộc vào thiết lập của admin

- > B Đúng

2. Có thể thay đổi scope của những config trong phần Store Configuration tương tự như có thể thay đổi đối với Product Attributes không?
   - A. Có
   - B. Không.
   - C. Tùy thuộc vào thiết lập của admin

- > A Chưa biết

3. 2 sp có thể có URL key giống nhau k?
   - A. Không.
   - B. Có, chỉ khi ít nhất 1 trong 2 sp là Not visible.
   - C. Có, chỉ khi cả 2 sp Not visible.
   - D. Không, nếu 2 sp cùng Visible ngoài frontend
   - E. Cả B và D đều đúng

- >  E

4. Chọn câu trả lời đúng nhất:
   2 CMS page có thể có URL key giống nhau không?
   - A. Có.
   - B. Không.
   - C. Có thể, chỉ khi 2 CMS page thuộc 2 storeviews khác nhau

- > C

5. Order ở trạng thái complete, khách hàng chỉ muốn refund shipping fee, không muốn refund bất kì sản phẩm nào. Điều này có khả thi không?
   - A. Có
   - B. Không.
   - C. Tùy thuộc vào thiết lập của admin

- > A
6. When creating an attribute, which of the following catalog input types can be used in layered navigation?
   - A. Date
   - B. Yes/No
   - C. Price
   - D. Both B&C
   - E. None of the above

- > D 

7. Khi tạo mới sp configurable, điền qty cho sp cha, stock status của sp cha là in stock, không điền Qty cho sp con. Vậy sau khi tạo sp xong, sp con có stock status là gì và ngoài frontend sp cha có stock status là gì?
   - A. Sp con: Out of stock, Frontend: Out of stock
   - B. Sp con: Out of stock, Frontend: In stock
   - C. Sp con: In stock, Frontend: In stock

- > A Đúng

8. 1 sp con có thể thuộc 2 sp cha configurable được không?
   - A. Có thể
   - B. Không thể

- > A

9. Storeview 1 và 2 cùng thuộc 1 website. 1 sp con có thể hiển thị trên category page của storeview 1 nhưng ko hiển thị trên category page tương ứng trên storeview 2 hay không?
   - A. Có thể
   - B. Không thể

- > A Đúng Assign to Store Views

10. Customer có thể tự xóa account ở FE không?
    - A Có
    - B Không
    - C Tùy thuộc thiết lập trong backend

- > B Đúng. Trong config của Account Information

11. Customer có thể đăng ký nhận email thông báo (hệ thống tự động gửi) trong những trường hợp nào sau đây:
    - A, Khi 1 sản phẩm có sự thay đổi về giá
    - B, Khi site có chương trình khuyến mại
    - C, Cả A & B đều có thể
    - D, Cả A và B đều không thể

- > C Đúng

12. Một custom er checkout as guest (đã có account nhưng không login) thì sau khi checkout có thể view order info trong My order page của account đó không?
    - A Có
    - B Không
    - C Tùy thuộc thiết lập trong backend

- > B

13. Khi có sản phẩm trong giỏ hàng, con số hiển thị bên phải mini cart icon có ý nghĩa gì?

- A, Số sản phẩm có trong giỏ hàng (không tính quantity)
- B, Số lượng sản phẩm có trong giỏ hàng (tổng quantity)
- C, Tùy thuộc vào thiết lập trong backend
- > B Đúng

14. Hai category page (thuộc cùng 1 storeview) có thể có bộ sort by (các attribute trong dropdown) khác nhau không?
    - A Có
    - B Không

- > B Đúng

15. Khi admin commen ở order, khách hàng chưa có account tại website magento có thể xem được comment này qua đâu
    - A. Email
    - B. Page order detail
    - C. Cả A&B
    - D. Khách hàng không thể xem được comment

- > A Order Comment Email Template for Guest

16. Một sản phẩm đang có qty=0, out of stock threshold=0, có thể refund order có sản phẩm nhưng không làm thay đổi stock status của sản phẩm không?
    - A. Có
    - B. Không

- > A RETURN TO STOCK
  > Magento adds quantities back to the products and sources that shipped the orders and reservation compensations to update salable quantities for the associated stock.

17. Có thể nào xảy ra trường hợp sản phẩm con của configurable product là sản phẩm con của bundle product hay không?
    - a. Có
    - b. Không
    - c. Tuỳ thiết lập của admin

- > C

18. Cho một grouped product có 1 sản phẩm con là sản phẩm con của configurable product. Khi set configurable product out stock (sản phẩm con vẫn instock và visibility ngoài FE) thì grouped product đã cho sẽ thế nào?
    - a. Hiển thị tất cả product con và add to cart các product con bình thường
    - b. Hiển thị tất cả product con và chỉ add to cart các product con trừ product con thuộc configurable product
    - c. Chỉ hiển thị các product con trừ product thuộc configurable product
    - d. Hiển thị tất cả product con và không thể add to cart bất cứ sản phẩm nào

- > A Đúng

19. Một sản phẩm vừa có tier price, vừa có special price thì ngoài Frontend sản phẩm đó sẽ hiển thị mức giá sale nào?
    - a. Hiển thị theo giá của special price
    - b. Phụ thuộc xem mức giá nào có lợi hơn cho người bán hàng thì hiển thị mức giá đó
    - c. Phụ thuộc xem mức giá nào có lợi hơn cho khách hàng thì hiển thị mức giá đó
    - d. Hiển thị giá sale = Original price – (tiger price + special price)
    - e. Có config cho phép lựa chọn hiển thị 1 trong 2 loại price trên

- > C

20. Có 2 configurantion giống nhau

- View product=> Advanced inventory=> notify for quantity below
- Store=> Configuration=> Catalog => Inventory=> product stock option=> notify for quantity below
  Vậy ý nghĩa và phạm vi hoạt động của 2 config trên có giống nhau không?
  - a. Có
  - b. Không
  - c. Tuỳ vào mục đích thiết lập từng config
- > B Không vì scope của nó là global

21. 2 sản phẩm cùng 1 website có thể có SKU trùng nhau không?
    - a. có
    - b. Không
    - d. Có thể khi duplicate sản phẩm

- > B Đúng vì scope là store view

22. Có 2 cart price rule lần lượt là Rule 1 và Rule 2 cùng được áp dụng cho sản phẩm A. Được biết Rule 1 có priority 1, Rule 2 có priority 2 và cả 2 rule đều enable config Discard subsequent. Cho biết khi thêm sản phẩm A vào cart thì rule nào sẽ được áp dụng.
    - a. Rule 1
    - b. Rule 2
    - c. Áp dụng rule 1 trước, rule 2 sau
    - d. Áp dụng rule 2 trước, rule1 sau

- > A Đúng priority 1 lớn hơn

23. Order chưa tạo invoice có thể taoj credit memo không?
    - a. có
    - b. không

- > B Đúng

24. Có thể áp dụng tax class khác nhau cho các sản phẩm khác nhau trong cùng 1 website không?
    - a. Không thể
    - b. Có thể
    - c. Có thể khi sản phẩm cùng 1 storeview

- > B Update Attribute

25. Import cùng 1 file chứa 5 sản phẩm vào nhiều lần mà không thay đổi thông tin trong file thì xảy ra hiện tượng gì?
    - a. Mỗi lần import thì số lượng sản phẩm sẽ tăng lên 5
    - b. Không thể import vì thông tin trong file trùng với data hiện tại của site
    - c. Không có gì xảy ra
    - d. Số lượng sản phẩm chỉ tăng lên 5.

- > D 

26. Có thể thêm trực tiếp configurable product từ cross-sell product vào cart không?
    - a. Có
    - b. Không

- > A B Phải thêm gián tiếp reason configurable phải có lựa chọn
