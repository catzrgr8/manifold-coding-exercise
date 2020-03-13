# manifold-coding-exercise

This lambda function is used in conjunction with API gateway and S3. API gateway receives requests from the web, lambda parses the JSON structure, and then creates a new object in S3. The fields first_name, middle_name, last_name, and zip_code are parsed out. Any extra data in the object could be stored as key value pairs in the csv file.
