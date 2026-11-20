# my-skills

Các kỹ năng (skill) Claude Code riêng của Khogao. Mỗi thư mục con là một kỹ năng, có `SKILL.md` và các tệp nó cần.

## Cài

Chép thư mục kỹ năng vào `~/.claude/skills/`:

```powershell
Copy-Item -Recurse -Force .\redpull "$env:USERPROFILE\.claude\skills\"
```

Sửa bản trong kho này rồi chép lại; bản trong `~/.claude/skills/` chỉ là bản đang chạy.

## Danh sách

| Kỹ năng | Làm gì | Cần gì |
|---|---|---|
| `redpull` | Tìm và đọc bài Reddit qua Reddit API chính thức (chỉ đọc), in Markdown gọn cho Claude đọc | Python + `requests`, khoá ứng dụng Reddit loại "script" trong `.env` cạnh `reddit_search.py` |

Không đưa khoá hay file `.env` lên kho.
