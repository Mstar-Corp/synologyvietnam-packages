# synologyvietnam-packages

Gói DSM (.spk) do Mstar Corp phát hành qua nguồn gói **https://packages.synologyvietnam.vn**.

- Tệp nằm ở **GitHub Releases** của repo này; mỗi release là một ảnh chụp đầy đủ các tệp feed đang phát.
- Nguồn chân lý là `releases.json` (manifest đã ký ed25519). Máy chủ feed CHỈ phát tệp có sha256 khớp manifest và chữ ký hợp lệ,
  nên tệp trên GitHub bị thay cũng không được phát.
- Thêm nguồn trong DSM: Package Center → Settings → Package Sources → Add → `https://packages.synologyvietnam.vn`.

Mã nguồn và quy trình phát hành nằm ở repo nội bộ mstar-connect.
