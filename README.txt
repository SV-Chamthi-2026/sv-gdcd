PHAN MEM CHAM TRAC NGHIEM GDCD - SAO THI ANH VAN (SV) - V5.11

Cach mo:
- Giai nen ZIP.
- Mo index.html bang Chrome/Edge. Camera can HTTPS hoac localhost; khi dua len hosting HTTPS, camera moi hoat dong on dinh.

Cau hinh va thao tac:
- Ba o Khối / Lớp / Phòng nam ngang va hoat dong doc lap.
- Khoi la bat buoc (mac dinh Khoi 6); lop va phong la tuy chon, co the de trong hoac chon dong thoi.
- Danh sach lop gom du 19 lop: 6D1-D4, 7D1-D5, 8D1-D4, 9D1-D6.
- Danh sach phong gom Phong 1 den Phong 10.
- 4 dot: GK1, CK1, GK2, CK2.
- Chon mau phieu cat phach (chup tu duong cat tro xuong) hoac khong cat phach (chup toan bo A4).
- Giao vien truc tiep chup/tai anh; toi da 50 anh/luot.
- Khi chay cham, moi anh goc duoc luu kem dong ket qua trong IndexedDB, giu nguyen thu tu giao vien gui len.
- Nut Xem anh goc mo lai anh da luu. Nut Chop/tai lai anh nay thay anh va doc lai tai dung vi tri cu, khong chen them phieu moi; ket qua cu bi huy de giao vien ra soat va tinh lai.
- Ket qua va anh goc duoc luu tren cung trinh duyet/thiet bi qua IndexedDB; khong tu dong dong bo Google Drive.

GIOI HAN QUAN TRONG:
- Hai mau phieu hien da co lua chon va huong dan chup, nhung chua co bo toa do hieu chuan rieng cho tung mau.
- OCR hien tai doc van ban tren toan anh, chua tach va nhan dang chinh xac 28 o dap an viet tay. Giao vien phai kiem tra/sua dap an truoc khi tinh va xac nhan diem.
- Chua tu dong doc ho ten/lop/so bao danh; chua tu dong ghep phach.
- Du lieu IndexedDB chi nam tren trinh duyet/thiet bi nay, KHONG tu dong dong bo Google Drive. Xoa du lieu trinh duyet co the mat du lieu. Hay xuat CSV va sao luu anh goc rieng.
- De lam quet tu dong dung cho ca hai mau, can cung cap anh/PDF mau chuan cua phieu cat phach va phieu khong cat phach (anh chup thang, ro cac duong ke va o dap an). Sau do moi hieu chuan toa do vung quet va kiem thu.

Khong dung ket qua OCR thu nghiem de chot diem chinh thuc khi chua duoc giao vien doi chieu.


LƯU ĐỢT CHẤM: Sau khi xử lý ảnh, kéo xuống mục “5. BÀI ĐÃ CHẤM / ĐÃ LƯU”, nhấn “Lưu đợt chấm”, nhập tên. Danh sách bản lưu xuất hiện tại mục này; có thể mở lại hoặc xóa. Dữ liệu lưu trong IndexedDB của trình duyệt trên thiết bị hiện tại, chưa đồng bộ đa thiết bị/Google Drive.


CAP NHAT MA TRAN DAP AN V5.11-SV:
- Man hinh Dap an hien thi dung bo cuc 2 hang x 14 cau theo phieu GDCD: hang 1 cau 1-14, hang 2 cau 15-28; moi o chon A/B/C/D.
- Moi danh sach cham luu bo dap an rieng trong IndexedDB tren trinh duyet hien tai. Khi mo danh sach khac, bo dap an duoc nap theo danh sach do.
- Bam “Luu cau hinh bai kiem tra tren may nay” de luu; thay doi dap an trong danh sach dang mo cung duoc luu tu dong.
- Chua co dong bo Google Drive. Chuc nang doc chu viet tay A/B/C/D tren tung o va danh dau tren anh chua duoc hoan thien.


CAP NHAT MAN HINH DAP AN:
- Khi bam Dap an, chi hien Muc 1 Cau hinh bai kiem tra va Muc 2 Dap an chuan. Cac muc 3 va 4 khong hien trong man hinh Dap an.
- Bang dap an chi co 28 cau, 2 hang x 14 cau; khong co cau 29-32.
- Co the nhap thu cong A/B/C/D hoac chon mot file/anh/PDF dap an de hien thi tham chieu. Ban nay chua tu dong OCR/trich dap an tu file/anh; giao vien van nhap/doi chieu trong 28 o.


SUA LOI CAMERA V5.11-SV:
- Hai nut “Mo camera chup truc tiep” va “Tai anh len” luon hien thi tren man hinh Cham bai.
- Bam “Dong camera” chi dong khung camera; nut Mo camera van con de mo lai bat cu luc nao.


FIX CAMERA BUTTON PERSISTENCE:
- Man hinh Cham bai co nut “Chup truc tiep” va “Tai anh len” doc lap voi khung camera.
- Dong camera chi an cameraPanel va dung stream; khong an/xoa nut “Chup truc tiep”. Nut nay nam ngoai cameraPanel de co the mo camera lai.


CAP NHAT GIAO DIEN CAMERA REV4:
- Nut Mo camera va Dong camera nam ngang hang, luon hien tren man hinh Cham bai.
- Nut Dong camera chi tat camera; hang nut dieu khien van con de mo lai.
- Nut Tai anh len nam rieng phia tren.
