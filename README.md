# aiozaneapi - An async wrapper made in Python for Zane API.

Example:
```py
client = aiozaneapi.Client('Token Here') # Instantiate the Client.
image = await client.magic('Image URL Here') # This will return a BytesIO object.
```