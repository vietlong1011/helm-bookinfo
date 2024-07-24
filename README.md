example  :https://istio.io/latest/docs/examples/bookinfo/![image](https://github.com/user-attachments/assets/824f3cbd-52c0-4451-aafa-373360660422)


https://raw.githubusercontent.com/istio/istio/release-1.21/samples/bookinfo/platform/kube/bookinfo.yaml

![image](https://github.com/user-attachments/assets/4870c50e-cf63-407e-adaa-6e515a96d622)
- productpage. Microservice productpagegọi detailsvà reviewsmicroservices để điền vào trang.

- details. Microservice detailschứa thông tin sách.

- reviews. Microservice reviewschứa các bài đánh giá sách. Nó cũng gọi ratingsmicroservice.

- ratings. Dịch ratingsvụ vi mô chứa thông tin xếp hạng sách đi kèm với bài đánh giá sách.


