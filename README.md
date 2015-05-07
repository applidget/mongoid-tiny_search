# Mongoid Tiny Search

This is under development and not recommended for production use yet. 

Basic and fast mongoid search 

Features :

- Add `searchable_keywords` field to the model you use
- Indexes are not defined by this gem, define your own
- Uses prefix regex to optimally use mongoid indexes
- Normalize the keywords to simplify simple characters (when possible) and be case insensitive
