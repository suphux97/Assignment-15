# Assignment-15
week 15
-- Count the total number of records in the dataset
SELECT COUNT(*) AS total_records FROM your_table;

-- Calculate the average age of social media users
SELECT AVG(age) AS avg_age FROM social_media_users;

-- Find the maximum number of seasons for Netflix shows
SELECT MAX(seasons) AS max_seasons FROM netflix_shows;

-- Sum the total number of casualties in human stampedes
SELECT SUM(casualties) AS total_casualties FROM human_stampedes;

-- Top 5 most liked posts on social media by engagement
SELECT post_id, post_content, likes
FROM social_media_posts
ORDER BY likes DESC
LIMIT 5;

-- Netflix genres with the highest average rating
SELECT genre, AVG(rating) AS avg_rating
FROM netflix_shows
GROUP BY genre
ORDER BY avg_rating DESC
LIMIT 5;

