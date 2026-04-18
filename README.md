# AltruMod
AltruMod is a non-commercial, opt-in moderation utility designed to assist volunteer moderators in support-oriented and high-stress subreddits (such as local city subreddits or advice forums). Its primary benefit is improving user safety and surfacing critical resources for Redditors in acute distress.

How it works:

The bot monitors incoming submissions in subreddits where the moderation team has explicitly invited and authorized it.

It uses standard keyword and regex matching (it does NOT scrape data for LLM or AI training) to identify posts indicating an urgent need for localized resources (e.g., housing crises, mental health distress, domestic safety issues).

It automatically posts a stickied comment containing a vetted list of external resources and subreddit-specific wiki links, ensuring the user gets immediate information.

It flags the post for the human moderation team to review.

Examples: If a user posts in a local city subreddit asking for emergency shelter options late at night, AltruMod will instantly pin a comment with the local 211 equivalent, local shelter directories, and crisis hotlines.

The bot will strictly adhere to rate limits, will not display ads, will not monetize user data, and clears all post IDs from memory after 24 hours to comply with Reddit's data retention and privacy policies.
