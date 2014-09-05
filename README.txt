Python 2.7.8 (default, Jun 30 2014, 16:08:48) [MSC v.1500 64 bit (AMD64)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> execfile('C:\\projects\\python\\twitter\\tweets.py')
>>> users = get_users(BASE_FOLDER_NAME)
>>> write_csv_from_all_users('tweets_summary.csv', users)
>>> 