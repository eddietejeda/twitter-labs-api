# 0.4.0 - 24 July 2020

- Better exception-handling: when API returns an error, a `TwitterLabsAPI::APIError` is thrown. It has the `Net::HTTP` response as an attribute so that the error can be handled properly. See the README for an example.


# 0.3.0 - 28 April 2020

- Fix: namespace of error class

# 0.2.0 - 5 March 2020

- Fix: Handle 'successful' API errors (i.e., HTTP 200 response, but API error such as User Not Found)
- Documented expansion fields
- Documented methods

# 0.1.0 - 5 March 2020

Initial gem commit