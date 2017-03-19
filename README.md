# Kaggle-Quora-Challenge
An open source, Python-based, NLP library:  http://www.nltk.org/

Kaggle Kernel:                              https://www.kaggle.com/edoarad/quora-question-pairs/can-i-rename-the-title-later

Stanford course:                            http://cs224n.stanford.edu/,  http://www.infocobuild.com/education/audio-video-courses/computer-science/cs224n-natural-language-processing.html

Google Cloud platform:                      https://cloud.google.com/pricing/free


Ideas:
- שאלות דומות נוטות להיות עם מילים דומות או זהות ובסדר דומה או זהה
- יש מילים שלמרות זאת הופכות את השאלות ללא דומות (או לפחות, ל-פחות דומות).
- למשל לחפש רפרנסים לזמנים ב-train set ולהוריד אותם
- ההסתברות ששאלות הן זהות בהינתן שמופיע בהן התג [math] היא מאוד נמוכה
- החלפות של מילים שלא באמת משנות, כמו do,can וכמו you, I
- גם צריך להבין איך מתמודדים עם מילים שההבדל הוא רק הטיה
- רעיון איך לגשת לבעיה: למצוא כל מני פונקציות דמיון היוריסטיות, שלא יהיו ה-predictor בעצמן אלא יהיו הפיצ'רים למודל כללי שנכניס אותם אליו, נניח ל-tree boosting. ואז אנחנו נשארים עם הבעיה של למצוא כל מני פונקציות של זוגות שאלות שיש בהן איזושהי אינפורמציה לגבי ה-duplicateness
- עדיף לחכות ל301
