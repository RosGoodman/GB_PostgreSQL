Отчет с кодом создания таблиц подписчиков на пользователей и сообщества.


CREATE TABLE user_subscriptions (
subscriber_user_id INT NOT NULL,
user_id INT NOT NULL,
PRIMARY KEY (subscriber_user_id, user_id)
);

CREATE TABLE subscriptions_to_communities (
subscriber_user_id INT NOT NULL,
community_id INT NOT NULL,
PRIMARY KEY (subscriber_user_id, community_id)
);