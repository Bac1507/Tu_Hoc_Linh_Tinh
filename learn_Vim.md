# Cùng học một số lệnh với VIM nhé 
## 1. Di chuyển trong VIM
* Sử dụng các dấu mũi tên
* Trong Vim hỗ trợ cách di chuyển nhanh chóng hơn là hjkl. Trong đó **h** là` left``,**j** là `down`, **k** là `up` và **l** là `right`

* Sử dụng **$** để di chuyển đến cuối dòng, **0** để di chuyển về đầu dòng, **shift + A** để di chuyển đến cuối dòng và chuyển luôn sang mode insert để thêm text . **gg** để di chuyển về đầu dòng đầu tiên và **shift+g** để di chuyển tới hàng cuối cùng.
 
## 2. Thoát Vim
* Để thoát vim và hủy bỏ tất cả thay đổi: về mode Normal với `ESC`, gõ `:q!`
* Để thoát vim mà chưa thay đổi gì : `:q`
* Thoát vim và lưu lại những thay đổi : `:wq`


## 3. Các lệnh xóa trong vim
* x: xóa 1 ký tự 
* dw: xóa đến ký tự bắt đầu từ tiếp theo
* de: xóa đến cuối của từ hiện tại
* d$: xóa đến cuối dòng
* dd: xóa 1 dòng

## 4. Các phím tắt
* dd : xóa 1 dòng 
* u: tương đương với ctrl+Z
* p: paste 

## Tìm kiếm 1 từ với /từ
* ví dụ : /vim , sau đó gõ `n` để đến các từ đó ở ví trí tiếp theo
* Thay thế 1 từ bằng 1 từ khác với `:/s/new/old/g`
  * Ví dụ: `:/s/vim/VIM/g`


## 
* o: thêm một dòng phía dưới dòng hiện tại 
* O: thêm một dòng phía trên dòng hiện tại
* a: insert vào phía sau ký tự hiện tại
* A: insert vào cuối dòng hiện tại.

   
