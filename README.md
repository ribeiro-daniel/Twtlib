## Twtlib - Lib to search and post on Twitter
## by Daniel Ribeiro

> Aviso:
- (en) To use this lib, you will need to have one: API_KEY, API_SECRET, TOKEN_KEY and TOKEN_SECRET, available from Twitter itself (developer.twitter.com)

- (pt) Para usar esta lib, será necessário possuir uma: API_KEY, API_SECRET, TOKEN_KEY e TOKEN_SECRET, disponibilizadas pelo próprio Twitter (developer.twitter.com)

> Install:

- pip install twtlib==1.0.0

> Import:

- from twtlib import Twtlib

> Methods:

- test = Twtlib(API_KEY, API_SECRET, TOKEN_KEY, TOKEN_SECRET) # put your credentials here

- test.buscar('keyword or #hashtags', 'lang') # example: test.buscar('Hello, world', 'en')
- test.postar('Anything') # example: test.postar('Hello, world!')




