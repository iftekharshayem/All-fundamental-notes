# 🚀 My Git & GitHub Learning Notes

GitHub-e code ebong notes manage korar jonno proyojoniyo shob commands:

## 1. Prothombar Setup korar jonno (Fresh Start)
Jokhon kono notun folder-ke Git-er sathe connect korte chao:

- `git init` 
  > **Kaj:** Ekta khali folder-ke Git repository-te rupantor kore.
- `git remote add origin [LINK]` 
  > **Kaj:** Tomar PC-r folder-er sathe GitHub-er online repository-r connection toiri kore.
- `git branch -M main` 
  > **Kaj:** Tomar main branch-er naam 'main' set kore.

---

## 2. Protibar Changes Push korar Magic Formula
Jokhon-i tumi kono file delete koro, edit koro ba notun file banao, ei 3-ta command sequence-e dite hoy:

1. `git add .` 
   > **Kaj:** Shob change ba notun file-ke Git-er "Staging Area"-te add kore (Mane Git-ke bole "Eigula ready koro").
2. `git commit -m "Tomar Message"` 
   > **Kaj:** Change-tar ekta permanent record ba "Snapshot" toiri kore. Message-e tumi ki kaj korecho ta likhte hoy.
3. `git push` 
   > **Kaj:** PC-te kora shob changes GitHub-er online server-e pathiye dey.

---

## 3. Kichu Gurutto-purno Tips
- **File Extension:** Note-er shundor look-er jonno `.txt` er bodole `.md` (Markdown) use kora bhalo.
- **README.md:** Ei nam-er file repository-r main page-e auto show kore.
- **Error "Not a git repository":** Ei error ashle bujhte hobe tumi vul folder-e acho ba `git init` kora hoyni. `cd` diye thik folder-e jete hobe.

---

## 4. Markdown Formatting (Note-er Beauty)
- `#` = Boro Heading
- `##` = Choto Heading
- `**Lekha**` = Bold (Ujjwal)
- `- ` = Bullet point list
-