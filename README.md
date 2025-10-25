{
  "name": "Journal Paper",
  "type": "light", // Важливо, щоб це була світла тема
  "colors": {
    // Основні кольори інтерфейсу
    "editor.background": "#FAF0E6",
    "editor.foreground": "#36454F",
    "editorCursor.foreground": "#A83232",
    "selection.background": "#E0E0E0",
    
    // Інші елементи (якщо потрібно)
    "sideBar.background": "#F5E6D8",
    "activityBar.background": "#E5D7C9",
    "statusBar.background": "#D4C7BB"
  },
  "tokenColors": [
    {
      "scope": [
        "comment"
      ],
      "settings": {
        "foreground": "#8A9A5B" // Коментарі
      }
    },
    {
      "scope": [
        "keyword",
        "storage"
      ],
      "settings": {
        "foreground": "#0047AB" // Ключові слова (як "чорнило")
      }
    },
    {
      "scope": [
        "string"
      ],
      "settings": {
        "foreground": "#964B00" // Рядки (як "коричневе чорнило")
      }
    }
    // Додайте інші елементи синтаксису (змінні, функції тощо) за бажанням
  ]
}
