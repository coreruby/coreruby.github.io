---
layout: post
title: The Perils of rescue Exception
category: posts
---

How often did you write code like this:

```ruby
begin
  call_a_method
rescue Exception => exc
  # Catch them all!
end
```

Don't be shy, we all did that. Learn why you should avoid, especially in Ruby
in [Mike Perham] post about [The Perils of rescue Exception].

[Mike Perham]: http://mikeperham.com/
[The Perils of rescue Exception]: http://mikeperham.com/2012/03/03/the-perils-of-rescue-exception/
