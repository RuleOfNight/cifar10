
- #Sử dụng dataset Cifar10 (link download: https://github.com/cyizhuo/CIFAR-10-dataset)

Trong file jupyter notebook thực hiện tuần tự các mục từ trên xuống như sau:
- Tạo 1 class dataloader nhận input là folder ảnh (train hoặc test) đó
- Tạo 1 model có sẵn bất kì (resnet18, ....)
- Tạo 1 optimizer bất kì (adamw,...)
- Sử dụng loss cross entropy
- Tiến hành trainning
- Cuối cùng đánh giá cả tập train và test bằng confusion matrix
- Lấy ra 2 ảnh đọc từ opencv và dùng model infer thử
