# GitHub Pages cho Comfy Mobile

1. Tạo một repository GitHub mới (public nếu dùng GitHub Free Pages).
2. Chép `index.html`, `endpoint.json` và `.nojekyll` trong thư mục này vào thư mục gốc repository.
3. Trong GitHub: **Settings → Pages → Deploy from a branch → main / root**.
4. Tạo Fine-grained Personal Access Token chỉ có quyền **Contents: Read and write** với đúng repository này.
5. Trong Control Center → Cấu hình → GitHub Pages, nhập Owner, Repository, Branch, đường dẫn `endpoint.json`, URL Pages và token.
6. Bật **Tự cập nhật khi Quick Tunnel đổi link**, lưu cấu hình rồi bấm **Cập nhật GitHub ngay**.

GitHub chỉ lưu địa chỉ tunnel hiện tại. Workflow, ảnh, model và dữ liệu ComfyUI không được tải lên GitHub.
