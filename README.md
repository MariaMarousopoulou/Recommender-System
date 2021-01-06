Recommender System (Cosine Similarity and Pearson Similarity)

This project were created by: George Skoufias, Marousopoulou Maria

1. Run as administrator setup.bat. This batch file is safe to run. Its purpose is to create a virtual environment in the current directory. Subsequently, it runs inside this environment a series of pip install commands based on a dependency descriptor file – requirements.txt – that is also included in the folder. In this manner the transferred project becomes of minimum size. If run as administrator does not work, navigate inside the project folder using command prompt. Run setup.bat from there.

2. From folder description execute: describe_books.py, describe_ratings.py, describe_users.py.

3. From folder popularity execute: author_popularity_outliers.py, book_popularity_outliers.py, readers_outliers.py, reading_activity.py, reader_age_analysis.py.

4. Change from file   C:\ProgramData\MySQL\MySQL Server 8.0\my.ini    the line      secure-file-priv="C:/ProgramData/MySQL/MySQL Server 8.0/Uploads"     TO    secure-file-priv="".

5. From folder migration\python execute: create_db.py, populate_db_infile.py, ratings_bins.py, user_recommender.py, new_similarity.py, new_age_similarity.py, age_recommender.py.
