{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "Statement1",
            "Effect": "Allow",
            "Principal": {
                "AWS": "*"
            },
            "Action": "s3:*",
            "Resource": [
                "arn:aws:s3:::Bucket-Name/*",
                "arn:aws:s3:::Bucket-Name"
            ]
        }
    ]
}