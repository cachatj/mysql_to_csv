loading data into BigQuery


CREATE OR REPLACE TABLE `prometheus-dev-392616.TLai_insights_posts.wp_posts` (
  `ID` INT64,
  `post_author` INT64 NOT NULL,
  `post_date` TIMESTAMP NOT NULL,
  `post_date_gmt` TIMESTAMP NOT NULL,
  `post_content` STRING NOT NULL,
  `post_title` STRING NOT NULL,
  `post_excerpt` STRING NOT NULL,
  `post_status` STRING DEFAULT 'publish',
  `comment_status` STRING DEFAULT 'open',
  `ping_status` STRING DEFAULT 'open',
  `post_password` STRING DEFAULT '',
  `post_name` STRING DEFAULT '',
  `to_ping` STRING NOT NULL,
  `pinged` STRING NOT NULL,
  `post_modified` TIMESTAMP DEFAULT TIMESTAMP "0001-01-01 00:00:00 UTC",
  `post_modified_gmt` TIMESTAMP DEFAULT TIMESTAMP "0001-01-01 00:00:00 UTC",
  `post_content_filtered` STRING NOT NULL,
  `post_parent` INT64 DEFAULT 0,
  `guid` STRING DEFAULT '',
  `menu_order` INT64 DEFAULT 0,
  `post_type` STRING DEFAULT 'post',
  `post_mime_type` STRING DEFAULT '',
  `comment_count` INT64 DEFAULT 0
);

