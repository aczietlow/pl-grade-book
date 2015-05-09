# Behat Tests

The purpose of this document is for establishing a standard on power leveling projects for how Behat tests will be written.

## Organizing features

Behat features should adhere to an organization schema to make them easier to maintain as the number of tests grow as the 
project grows. The feature files should all be in the ./features directory and use the following naming schema: business object
followed by action followed by context if it's needed.

    user.feature
    user_login.feature
    user_registration.feature
    node_news_delete.feature
    node_news_create.feature
    node_news_create_to_be_published_in_the_future.feature
    