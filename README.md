# Dự án QLPM

Đầu tiên mọi người clone repo về máy.

Các bước sử dụng và đọc docs free của OpenAI:
- Tải python phiên bản mới nhất.
- Mở CLI cd đến thư mục repo và chạy lệnh sau:
- ```pip install "llama-cpp-python==0.2.28"  --upgrade --force-reinstall --no-cache-dir```
- ```pip install "llama-cpp-python[server]0.2.28"  --upgrade --force-reinstall --no-cache-dir```
- ```pip install -r requirement.txt```
- Sau đó mọi người lên [HuggingFace](https://huggingface.co/models "Nơi tải model OpenAI về") để tải model ai về, hiện tại ưu tiên Text Generation.
- Thả file vừa  vào thư mục models ở repo.
- Sau đó chạy lệnh ```python -m llama_cpp.server --model "Tên-model.đuôi" --chat_format chatml --n_gpu_layers 35```
- Vào đường dẫn [này](http://localhost:8000/docs) để đọc thông tin về API của OpenAI.
