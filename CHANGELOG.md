# 0.0.5

- Bug fix
- Remove `require 'rails'` from spec_helper.rb
- Remove rails dependences (blank? method) in code
- Spec fix

# 0.0.4

- Add specs for almost all classes
- Add a method `to_json` for WebImage class to be able to get a usable array of images' attributes

# 0.0.3

- Add specs for LinkThumbnailer class
- Refactor config system, now using dedicated configuration class

# 0.0.2

- Added Rspec
- Bug fixes:
	- Now checking if attribute is blank for LinkThumbnailer::Object.valid? method

# 0.0.1

- LinkThumbnailer::Object
- LinkThumbnailer::Doc
- LinkThumbnailer::DocParser
- LinkThumbnailer::Fetcher
- LinkThumbnailer::ImgComparator
- LinkThumbnailer::ImgParser
- LinkThumbnailer::ImgUrlFilter
- LinkThumbnailer::Opengraph
- LinkThumbnailer::WebImage
- LinkThumbnailer.configure
- LinkThumbnailer.generate