# AsyncTaskLesson_1
Start аndroid: Урок 86. AsyncTask. Знакомство, несложный пример (программирование под android)
 https://www.youtube.com/watch?v=ks4lPf9RAPY&amp;list=PLyfVjOYzujugap6Rf3ETNKkx4v9ePllNK&amp;index=89
  4 правила использования AsyncTask:
  - объект AsyncTask должен быть создан в UI-потоке
  - метод execute должен быть вызван в UI-потоке
  - не вызывайте напрямую методы onPreExecute, doInBackground, onPostExecute и onProgressUpdate (последний мы пока не проходили)
  - AsyncTask может быть запущен (execute) только один раз, иначе будет exception
