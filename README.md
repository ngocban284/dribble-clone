# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Các gem được sử dụng 
* bulma-rails : framework của css tương tự bootstrap
* devise : khuôn mẫu dùng để xác thực đăng nhập , sing_in,log_in ...v.v
* carrierwave : cung cấp chức năng upload , đăng tải hình ảnh| model thêm mount_uploader:ten_thuoc_tinh , ten_thuoc_tinhUpLoader 
* simple_form : cung cấp 1 simple_form dùng trong view
* mini_magick : Thao tác hình ảnh với mức sử dụng bộ nhớ tối thiểu
* impressionist : dùng để đếm lượt xem của 1 đối tượng .is_impressionable đặt trong model đối tượng , impressionist đặt trong controller. 
                                                                                        Tra cứu view :  @model.impression.count
* jquery-rails : jQuery cung cấp các phương thức xử lý sự kiện, hiệu ứng, tương tác  chỉ với những dòng lệnh đơn giản
* gravatar : cung cấp cách thức lấy ảnh đại diện qua mail
* acts_as_votable : cung cấp chức nặng like , dislike . acts_as_votable thêm vào Model đc vote | acts_as_voter thêm vào model đi vote
* guard : Guard là một công cụ dòng lệnh để dễ dàng xử lý các sự kiện về sửa đổi hệ thống tệp.
* guard livereload : tự động reload lại server khi các mục trong view được sửa đổi 
* better_errors : bắt lỗi tốt hơn 

# các hàm lạ 
* <%= truncate(shot.description, length: 60) %> : dùng để giới hạn độ dài 
* <%= time_ago_in_words(@shot.created_at) %> : hiển thị thời gian đối tượng được tạo 
<%= pluralize(@shot.comments.count, 'Comment') %> :  in ra số lượng của đối số 
