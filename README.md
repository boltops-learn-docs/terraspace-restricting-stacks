<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-restricting-stacks/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Restricting Stacks

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

An example Terraspace project to show how to use the options:

config/app.rb

```ruby
Terraspace.configure do |config|
  config.allow.stacks = ["stack1"]
  # config.deny.stacks = ["stack1"]
end
```

## Usage

Uncomment out the examples in `config/app.rb` and run:

    TS_ENV=dev    terraspace up stack1
    TS_ENV=prod   terraspace up stack2
    TS_ENV=global terraspace up route53

## Video

[![Watch the video](https://uploads-learn.boltops.com/pcsmvsrn6qn3y6ki91l5y3e95q26)](https://learn.boltops.com/courses/terraspace-fundamentals/lessons/terraspace-config-allow-and-deny-stacks-for-specific-environments)

Note: Premium video content requires a subscription.
