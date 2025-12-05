<div style="text-align:center; padding:80px 20px; max-width:800px; margin:0 auto;">
  <h1 style="font-size:3.2em; background: linear-gradient(90deg, var(--neon-color), var(--neon-color2)); -webkit-background-clip: text; color: transparent;">
    Blog Lập Trình
  </h1>
  <p style="font-size:1.4em; color:#ccc; margin:30px 0;">
    Java • JavaScript • Lập trình mạng • Mini project
  </p>
  <hr style="max-width:300px; margin:40px auto; border-color: var(--neon-color);">
</div>

{{/* Khi chưa có bài viết nào sẽ hiện thông báo đẹp */}}
{{ if not (where site.RegularPages "Section" "blog") }}
<div style="text-align:center; padding:60px 20px; color:#aaa;">
  <p style="font-size:1.3em;">Blog đang được mình chuẩn bị nội dung kỹ lưỡng</p>
  <p>Sắp tới sẽ có <strong>hơn 12 bài chi tiết</strong> về Java IO, đa luồng, Socket, JavaScript DOM, Async/Await, mini project thực tế…</p>
  <p style="margin-top:30px;"><em>Quay lại sau vài ngày nhé!</em></p>
</div>
{{ end }}