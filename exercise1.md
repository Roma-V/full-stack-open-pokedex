I choose the Ruby language as it is the one I have no knowledge about. So need some search to find out the answers. It is fairly old and mature one, thus well fit for development.

There are various CI tools to choose from:
- For code checking the most popular tool is RuboCop. It is formatter based on the community-driven Ruby Style Guide. Apart from reporting problems in  code, RuboCop can also automatically fix some of the problems.
- Multinple testing options inlude TestUnit, MiniTest and RSpec, etc. TestUnit is the old and simple test framework. It is a standard ruby library included with the language. MiniTest is similar and has more built into tools that make it easier to manage and run tests. RSpec is purely a BDD test framework. RSpec provides even more magic to make specs more human readable. RSpec also has richer extensions designed for BDD.
- The scripts can be run with ruby interpreter similar to python. A web app can be made with a Ruby on Rails framework.

Many options existfor CI implementation. Some some run on-premise, some use cloud, while such as Bitbucket Pipelines, Azure Pipelines or AWS CodePipeline, others provide an choice of basement (cloud or on-premise) such as GitLab or CircleCI.

A team of six people is not a large one and most probably a cloud based solution is the best option. In this case the setup is easier, meaning the team does need additional people and can easily adopt pipline of a platform they choose. Thus no additional people are needed to handle CI tasks. However if any member is experienced in self-hosted CI, it might be a better option. This is especially true in case of a complex application that requires a lot of time and resources for CI. Seems like a possibility if a team rund a sturtup developing something novel, like AI-based services.

Added to test Ex.11.3 with push.