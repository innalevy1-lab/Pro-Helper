# Pro-Helper
Short: AI writing tutor for Pro-Seminar students (Dr. Inna Levy, Ariel University). Guides students through research paper writing — gives feedback, helps structure arguments, checks APA. Does not write for students. Built with Claude API. Hebrew interface.
| Pro-Seminar Writing Tutor

למה הבוט הזה נוצר?
1. כתיבת עבודה מחקרית היא תהליך — לא רק תוצר.
2. הבוט הזה נועד ללוות אותך לאורך כל שלבי הכתיבה: מניסוח שאלת המחקר ועד לכתיבת הדיון.
3. הבוט לא כותב במקומך. הוא עוזר לך לחשוב, לתכנן ולשפר בעצמך.

מה הבוט יכול לעשות?
א. לעזור להבין את דרישות העבודה והמבנה שלה
ב. לתת משוב על טיוטות שכתבת
ג. לעזור לנסח שאלת מחקר והשערה
ד. ללוות בכתיבת המבוא וסקירת הספרות
ה. לבדוק ציון מקורות לפי APA — כשאת/ה מספק/ת את פרטי המקור
ו. לעזור בכתיבת רפלקציה על תהליך הכתיבה

איך משתמשים?
1. פתחו את הקובץ בדפדפן
2. כתבו את שאלתכם בעברית
3. הביאו טיוטה, פסקה, שאלת מחקר — או כל שלב בעבודה

💡 טיפ: הבוט עובד הכי טוב כשמביאים טקסט שכתבתם ומבקשים משוב — לא כשמבקשים ממנו לכתוב עבורכם.

פרטי הקורס
קורספרו-סמינריון בקרימינולוגיהמרצהד"ר אינה לוימוסדאוניברסיטת אריאלשנת לימודיםתשפ"ומועד הגשה20.7.2026

שאלות נוספות?
פנו למרצה דרך אתר הקורס או >אימייל: inna.levy1@gmail.com 


Technical notes (English)
This is a single-file HTML chatbot powered by the Anthropic Claude API (claude-sonnet-4-20250514).
Pedagogical model
The bot follows a coaching model, not a writing model, based on three principles:
1. It never writes submission-ready text for students
2. It never fabricates sources or bibliographic details
3. Every meaningful interaction ends with three reflection questions (intention → gap → next step)

Stack: Pure HTML/CSS/JS — no framework, no build step/ Claude API via fetch (client-side)/ Requires an Anthropic API key to run
Deployment: Designed for deployment via GitHub Pages or any static hosting service. Students access via a shared URL — no login or installation required.
Course context: Pro-Seminar in Social Sciences, Ariel University, Israel. Academic year 2025–2026.
