# Ruby & Rails Gems Compendium

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A curated collection of Ruby gems and Rails libraries, organized by category. Sourced from personal starred repositories on GitHub.

---

## Table of Contents

1. [Web Frameworks & Servers](#1-web-frameworks--servers)
2. [Authentication & Authorization](#2-authentication--authorization)
3. [Background Jobs & Queues](#3-background-jobs--queues)
4. [API & Serialization](#4-api--serialization)
5. [GraphQL](#5-graphql)
6. [Database & ActiveRecord](#6-database--activerecord)
7. [Database Migrations & Safety](#7-database-migrations--safety)
8. [Multi-tenancy](#8-multi-tenancy)
9. [Audit & Versioning](#9-audit--versioning)
10. [Testing](#10-testing)
11. [Test Performance & Parallelization](#11-test-performance--parallelization)
12. [Code Coverage](#12-code-coverage)
13. [Code Quality & Linting](#13-code-quality--linting)
14. [Performance & Profiling](#14-performance--profiling)
15. [Monitoring & Observability](#15-monitoring--observability)
16. [Resiliency & Circuit Breakers](#16-resiliency--circuit-breakers)
17. [Admin Panels](#17-admin-panels)
18. [Feature Flags](#18-feature-flags)
19. [Notifications & Email](#19-notifications--email)
20. [Payments](#20-payments)
21. [AI & LLM Integration](#21-ai--llm-integration)
22. [MCP (Model Context Protocol)](#22-mcp-model-context-protocol)
23. [Frontend & Hotwire](#23-frontend--hotwire)
24. [Web Scraping](#24-web-scraping)
25. [Markdown & Documentation](#25-markdown--documentation)
26. [I18n & Localization](#26-i18n--localization)
27. [Async & Concurrency](#27-async--concurrency)
28. [Kafka & Messaging](#28-kafka--messaging)
29. [A/B Testing & Experimentation](#29-ab-testing--experimentation)
30. [Type Systems & Static Analysis](#30-type-systems--static-analysis)
31. [Modularization & Architecture](#31-modularization--architecture)
32. [CLI & Tools](#32-cli--tools)
33. [QR Codes, Calendar & Misc Utilities](#33-qr-codes-calendar--misc-utilities)
34. [Asset Pipeline](#34-asset-pipeline)
35. [Ruby Implementations & Compatibility](#35-ruby-implementations--compatibility)
36. [Cross-language & Interop](#36-cross-language--interop)
37. [Real-World Apps (Open Source)](#37-real-world-apps-open-source)
38. [Style Guides & Best Practices](#38-style-guides--best-practices)
39. [Learning & Resources](#39-learning--resources)
40. [Rails-specific Dev Tools & Skills](#40-rails-specific-dev-tools--skills)
41. [Rails DOM & Testing Helpers](#41-rails-dom--testing-helpers)

---

## 1. Web Frameworks & Servers

| Gem | Description |
|-----|-------------|
| [rails](https://github.com/rails/rails) | Ruby on Rails, the full-stack web framework |
| [rage](https://github.com/rage-rb/rage) | Ruby framework for non-blocking I/O |
| [puma](https://github.com/puma/puma) | A Ruby/Rack web server built for parallelism |
| [falcon](https://github.com/socketry/falcon) | High-performance web server supporting HTTP/1, HTTP/2 and TLS |
| [rackup](https://github.com/rack/rackup) | Rack server interface |

## 2. Authentication & Authorization

| Gem | Description |
|-----|-------------|
| [pundit](https://github.com/varvet/pundit) | Object-oriented authorization with plain Ruby classes |
| [omniauth](https://github.com/omniauth/omniauth) | Flexible authentication with Rack middleware |
| [doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) | OAuth 2 provider for Rails and Grape |
| [devise_token_auth](https://github.com/lynndylanhurley/devise_token_auth) | Token-based authentication for Rails APIs |
| [devise-jwt](https://github.com/waiting-for-dev/devise-jwt) | JWT authentication with Devise and Rails |
| [ruby-jwt](https://github.com/jwt/ruby-jwt) | Ruby implementation of JSON Web Tokens (RFC 7519) |
| [authentication-zero](https://github.com/lazaronixon/authentication-zero) | Authentication generator for Rails |
| [revise_auth](https://github.com/excid3/revise_auth) | Pure Rails authentication system |
| [stytch-ruby](https://github.com/stytchauth/stytch-ruby) | Stytch SDK for Ruby |
| [rolify](https://github.com/RolifyCommunity/rolify) | Role management with resource scoping |
| [strong_password](https://github.com/bdmac/strong_password) | Password strength validation |

## 3. Background Jobs & Queues

| Gem | Description |
|-----|-------------|
| [good_job](https://github.com/bensheldon/good_job) | Multithreaded Active Job backend using Postgres |
| [solid_queue](https://github.com/rails/solid_queue) | Database-backed Active Job backend |
| [mission_control-jobs](https://github.com/rails/mission_control-jobs) | Dashboard and administration for Active Job |
| [job-iteration](https://github.com/Shopify/job-iteration) | Interruptible and resumable jobs |
| [sidekiq-throttled](https://github.com/ixti/sidekiq-throttled) | Throttling for Sidekiq |
| [sidekiq-history](https://github.com/russ/sidekiq-history) | Sidekiq job history |
| [active_job_log](https://github.com/platanus/active_job_log) | Job history logging |

## 4. API & Serialization

| Gem | Description |
|-----|-------------|
| [blueprinter](https://github.com/procore-oss/blueprinter) | Declarative JSON serialization |
| [alba](https://github.com/okuramasafumi/alba) | Fast JSON serializer for Ruby |
| [jsonapi-serializer](https://github.com/jsonapi-serializer/jsonapi-serializer) | JSON:API compliant serializer (Netflix fast_jsonapi fork) |
| [jsonapi.rb](https://github.com/stas/jsonapi.rb) | Lightweight JSON:API for Ruby |
| [props_template](https://github.com/thoughtbot/props_template) | Fast JSON builder for Rails |
| [json_matchers](https://github.com/thoughtbot/json_matchers) | Validate JSON API responses in tests |
| [json-schema](https://github.com/voxpupuli/json-schema) | JSON Schema validator |
| [rack-cors](https://github.com/cyu/rack-cors) | CORS middleware for Rack-compatible web applications |

## 5. GraphQL

| Gem | Description |
|-----|-------------|
| [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) | GraphQL implementation for Ruby |
| [graphiql-rails](https://github.com/rmosolgo/graphiql-rails) | GraphiQL IDE for Rails applications |

## 6. Database & ActiveRecord

| Gem | Description |
|-----|-------------|
| [ancestry](https://github.com/stefankroes/ancestry) | Tree structures for ActiveRecord |
| [scenic](https://github.com/scenic-views/scenic) | Versioned database views |
| [fx](https://github.com/teoljungberg/fx) | Versioned database functions and triggers |
| [activerecord-import](https://github.com/zdennis/activerecord-import) | Bulk insert for ActiveRecord |
| [active_record-acts_as](https://github.com/chaadow/active_record-acts_as) | Multi-table inheritance for ActiveRecord |
| [foreigner](https://github.com/matthuhiggins/foreigner) | Foreign keys in migrations |
| [active_type](https://github.com/makandra/active_type) | Make any Ruby object quack like ActiveRecord |
| [store_attribute](https://github.com/palkan/store_attribute) | Typecasting for store accessors |
| [after_commit_everywhere](https://github.com/Envek/after_commit_everywhere) | Transactional callbacks outside of models |
| [discard](https://github.com/jhawthorn/discard) | Soft deletes for ActiveRecord |
| [ransack](https://github.com/activerecord-hackery/ransack) | Object-based searching |
| [neighbor](https://github.com/ankane/neighbor) | Nearest neighbor search for ActiveRecord |
| [pgvector-ruby](https://github.com/pgvector/pgvector-ruby) | pgvector support for Ruby |
| [redis-objects](https://github.com/nateware/redis-objects) | Map Redis types to Ruby objects |
| [dalli](https://github.com/petergoldstein/dalli) | High-performance Memcached client |

## 7. Database Migrations & Safety

| Gem | Description |
|-----|-------------|
| [strong_migrations](https://github.com/ankane/strong_migrations) | Detect unsafe migrations |
| [data-migrate](https://github.com/ilyakatz/data-migrate) | Data migrations for Rails |
| [next_rails](https://github.com/fastruby/next_rails) | Toolkit for Rails upgrades |

## 8. Multi-tenancy

| Gem | Description |
|-----|-------------|
| [acts_as_tenant](https://github.com/ErwinM/acts_as_tenant) | Multi-tenancy with shared database |
| [apartment](https://github.com/influitive/apartment) | Multi-tenancy for Rack and Rails |
| [activerecord-tenanted](https://github.com/basecamp/activerecord-tenanted) | Separate databases per tenant |

## 9. Audit & Versioning

| Gem | Description |
|-----|-------------|
| [paper_trail](https://github.com/paper-trail-gem/paper_trail) | Track changes to ActiveRecord models |
| [logidze](https://github.com/palkan/logidze) | Database change log for Rails |
| [audit-log](https://github.com/rails-engine/audit-log) | Audit logs with built-in UI |

## 10. Testing

| Gem | Description |
|-----|-------------|
| [rspec-rails](https://github.com/rspec/rspec-rails) | RSpec testing framework for Rails |
| [minitest](https://github.com/minitest/minitest) | Complete testing suite for Ruby |
| [capybara](https://github.com/teamcapybara/capybara) | Acceptance testing framework |
| [cuprite](https://github.com/rubycdp/cuprite) | Capybara driver for headless Chrome via CDP |
| [ferrum](https://github.com/rubycdp/ferrum) | Ruby API for Chrome DevTools Protocol |
| [capybara_accessible_selectors](https://github.com/citizensadvice/capybara_accessible_selectors) | Accessible selectors for Capybara |
| [vcr](https://github.com/vcr/vcr) | Record and replay HTTP interactions in tests |
| [testcontainers-ruby](https://github.com/testcontainers/testcontainers-ruby) | Testcontainers for Ruby |
| [fixturebot](https://github.com/rubymonolith/fixturebot) | Fixtures with factory-style syntax |
| [rspec_junit_formatter](https://github.com/sj26/rspec_junit_formatter) | JUnit XML formatter for RSpec |
| [webdrivers](https://github.com/titusfortner/webdrivers) | Auto-update WebDrivers |

## 11. Test Performance & Parallelization

| Gem | Description |
|-----|-------------|
| [parallel_tests](https://github.com/grosser/parallel_tests) | Run tests in parallel (2x+ speedup) |
| [flatware](https://github.com/briandunn/flatware) | Parallel test runner |
| [quickdraw](https://github.com/yippee-fun/quickdraw) | Multi-core test runner |
| [test-queue](https://github.com/tmm1/test-queue) | Parallel test runner for CI |
| [knapsack](https://github.com/KnapsackPro/knapsack) | Optimal test distribution across CI nodes |
| [test-prof](https://github.com/test-prof/test-prof) | Test profiling toolbox |

## 12. Code Coverage

| Gem | Description |
|-----|-------------|
| [simplecov](https://github.com/simplecov-ruby/simplecov) | Code coverage with powerful configuration |
| [coverband](https://github.com/danmayer/coverband) | Production code coverage |
| [undercover](https://github.com/grodowski/undercover) | Detect untested code changes |
| [rcov](https://github.com/relevance/rcov) | Code coverage tool (legacy) |

## 13. Code Quality & Linting

| Gem | Description |
|-----|-------------|
| [rubocop](https://github.com/rubocop/rubocop) | Static analyzer and code formatter |
| [brakeman](https://github.com/presidentbeef/brakeman) | Security scanner for Rails |
| [reek](https://github.com/troessner/reek) | Code smell detector |
| [skunk](https://github.com/fastruby/skunk) | SkunkScore: complexity without coverage |
| [rubycritic](https://github.com/whitesmith/rubycritic) | Code quality report |
| [pronto](https://github.com/prontolabs/pronto) | Automated code review |
| [pronto-rubocop](https://github.com/prontolabs/pronto-rubocop) | Pronto runner for RuboCop |
| [bundler-audit](https://github.com/rubysec/bundler-audit) | Security audit for Bundler dependencies |
| [overcommit](https://github.com/sds/overcommit) | Git hook manager |
| [callback_hell](https://github.com/evilmartians/callback_hell) | Analyzer for Rails callbacks |

## 14. Performance & Profiling

| Gem | Description |
|-----|-------------|
| [bullet](https://github.com/flyerhzm/bullet) | Detect N+1 queries and unused eager loading |
| [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) | Profiler for development and production |
| [rails_performance](https://github.com/igorkasyanchuk/rails_performance) | Self-hosted performance monitor |
| [ruby-prof](https://github.com/ruby-prof/ruby-prof) | Fast code profiler for Ruby |
| [stackprof](https://github.com/tmm1/stackprof) | Sampling call-stack profiler |
| [rbspy](https://github.com/rbspy/rbspy) | CPU profiler for Ruby |
| [debugbar](https://github.com/julienbourdeau/debugbar) | Devtools for Rails |
| [fast-ruby](https://github.com/fastruby/fast-ruby) | Fast Ruby idioms and benchmarks |
| [fast_blank](https://github.com/SamSaffron/fast_blank) | Fast implementation of String#blank? |
| [fast_underscore](https://github.com/kddnewton/fast_underscore) | Fast implementation of String#underscore |
| [sniffer](https://github.com/aderyabin/sniffer) | Log outgoing HTTP requests |

## 15. Monitoring & Observability

| Gem | Description |
|-----|-------------|
| [yabeda](https://github.com/yabeda-rb/yabeda) | Extensible metrics framework |
| [upright](https://github.com/basecamp/upright) | Synthetic monitoring with Playwright |
| [rails_semantic_logger](https://github.com/reidmorrison/rails_semantic_logger) | Semantic logging for Rails |

## 16. Resiliency & Circuit Breakers

| Gem | Description |
|-----|-------------|
| [semian](https://github.com/Shopify/semian) | Resiliency toolkit for failing external services |
| [stoplight](https://github.com/bolshakov/stoplight) | Traffic light-based circuit breaker |
| [isolator](https://github.com/palkan/isolator) | Detect non-atomic interactions within transactions |

## 17. Admin Panels

| Gem | Description |
|-----|-------------|
| [activeadmin](https://github.com/activeadmin/activeadmin) | Administration framework for Rails |
| [rails_admin](https://github.com/railsadminteam/rails_admin) | Admin engine for Rails |
| [madmin](https://github.com/excid3/madmin) | Robust admin interface |
| [administrate](https://github.com/thoughtbot/administrate) | Flexible admin dashboard framework |

## 18. Feature Flags

| Gem | Description |
|-----|-------------|
| [flipper](https://github.com/flippercloud/flipper) | Feature flags for Ruby |
| [feature](https://github.com/mgsnova/feature) | Feature toggles |
| [feature_toggles](https://github.com/bibendi/feature_toggles) | Feature toggles for pending features |

## 19. Notifications & Email

| Gem | Description |
|-----|-------------|
| [noticed](https://github.com/excid3/noticed) | Notification system for Rails |
| [exception_notification](https://github.com/smartinez87/exception_notification) | Exception notifier for Rails |
| [mjml-rails](https://github.com/sighmon/mjml-rails) | MJML templates for Rails emails |
| [unsubscribe](https://github.com/stevepolitodesign/unsubscribe) | Auto-unsubscribe from emails |
| [action_push_native](https://github.com/rails/action_push_native) | Native push notifications for mobile |

## 20. Payments

| Gem | Description |
|-----|-------------|
| [pay](https://github.com/pay-rails/pay) | Payments engine for Rails |
| [sdk-ruby](https://github.com/mercadopago/sdk-ruby) | MercadoPago SDK for Ruby |

## 21. AI & LLM Integration

| Gem | Description |
|-----|-------------|
| [ruby_llm](https://github.com/crmne/ruby_llm) | Unified API for multiple LLM providers |
| [ruby-openai](https://github.com/alexrudall/ruby-openai) | OpenAI client for Ruby |
| [ruby-anthropic](https://github.com/alexrudall/ruby-anthropic) | Anthropic (Claude) client for Ruby |
| [langchainrb](https://github.com/patterns-ai-core/langchainrb) | LangChain for Ruby |
| [langchainrb_rails](https://github.com/patterns-ai-core/langchainrb_rails) | LangChain integration for Rails |
| [raif](https://github.com/CultivateLabs/raif) | Ruby AI Framework |
| [activeagent](https://github.com/activeagents/activeagent) | AI agents framework for Rails |
| [tiktoken_ruby](https://github.com/IAPark/tiktoken_ruby) | Tiktoken tokenization for Ruby |
| [rumale](https://github.com/yoshoku/rumale) | Machine learning library for Ruby |
| [roast](https://github.com/Shopify/roast) | Structured AI workflows |
| [top_secret](https://github.com/thoughtbot/top_secret) | Filter PII before sending to LLMs |

## 22. MCP (Model Context Protocol)

| Gem | Description |
|-----|-------------|
| [fast-mcp](https://github.com/yjacquin/fast-mcp) | MCP implementation in Ruby |
| [rails-mcp-server](https://github.com/maquina-app/rails-mcp-server) | MCP server for Rails projects |
| [nvim-mcp-server](https://github.com/maquina-app/nvim-mcp-server) | MCP server for Neovim |
| [ruby-mcp-client](https://github.com/simonx1/ruby-mcp-client) | MCP client in Ruby |
| [chatwerk](https://github.com/rubyatscale/chatwerk) | MCP for Packwerk |

## 23. Frontend & Hotwire

| Gem | Description |
|-----|-------------|
| [turbo-rails](https://github.com/hotwired/turbo-rails) | Turbo integration for Rails |
| [jsbundling-rails](https://github.com/rails/jsbundling-rails) | JS bundling with esbuild, Bun, rollup, or webpack |
| [cssbundling-rails](https://github.com/rails/cssbundling-rails) | CSS bundling with Tailwind, PostCSS, Sass, and more |
| [tailwindcss-rails](https://github.com/rails/tailwindcss-rails) | Tailwind CSS for Rails |
| [ruby_ui](https://github.com/ruby-ui/ruby_ui) | UI components for Ruby |
| [showcase](https://github.com/bullet-train-co/showcase) | Component previews for Rails |
| [superglue](https://github.com/thoughtbot/superglue) | Rails + React + Redux integration |
| [sweet-alert2-rails](https://github.com/nicolasblanco/sweet-alert2-rails) | SweetAlert2 for Rails |
| [marksmith](https://github.com/avo-hq/marksmith) | GitHub-style Markdown editor |
| [ruby2js](https://github.com/ruby2js/ruby2js) | Convert Ruby to JavaScript |

## 24. Web Scraping

| Gem | Description |
|-----|-------------|
| [kimuraframework](https://github.com/vifreefly/kimuraframework) | Web scraping framework with AI support |
| [wombat](https://github.com/felipecsl/wombat) | Web scraper with an elegant DSL |
| [tanakai](https://github.com/glaucocustodio/tanakai) | Modern fork of Kimurai framework |

## 25. Markdown & Documentation

| Gem | Description |
|-----|-------------|
| [kramdown](https://github.com/gettalong/kramdown) | Pure Ruby Markdown parser |
| [redcarpet](https://github.com/vmg/redcarpet) | Safe and fast Markdown processor |
| [commonmarker](https://github.com/gjtorikian/commonmarker) | Ruby wrapper for CommonMark parser |
| [rdoc](https://github.com/ruby/rdoc) | HTML documentation generator for Ruby |
| [yard](https://github.com/lsegal/yard) | Ruby documentation tool |

## 26. I18n & Localization

| Gem | Description |
|-----|-------------|
| [globalize](https://github.com/globalize/globalize) | Model translation for ActiveRecord |

## 27. Async & Concurrency

| Gem | Description |
|-----|-------------|
| [async](https://github.com/socketry/async) | Event-driven concurrency reactor for Ruby |
| [goru](https://github.com/bryanp/goru) | Concurrent routines without threads |
| [anycable-rails](https://github.com/anycable/anycable-rails) | High-performance WebSockets for Rails |

## 28. Kafka & Messaging

| Gem | Description |
|-----|-------------|
| [karafka](https://github.com/karafka/karafka) | Kafka framework for Ruby and Rails |
| [rdkafka-ruby](https://github.com/karafka/rdkafka-ruby) | Kafka client based on librdkafka |
| [ruby-kafka](https://github.com/zendesk/ruby-kafka) | Kafka client for Ruby |

## 29. A/B Testing & Experimentation

| Gem | Description |
|-----|-------------|
| [split](https://github.com/splitrb/split) | Rack-based A/B testing framework |
| [scientist](https://github.com/github/scientist) | Safe refactoring of critical code paths |

## 30. Type Systems & Static Analysis

| Gem | Description |
|-----|-------------|
| [ruby-lsp](https://github.com/Shopify/ruby-lsp) | Language server for Ruby |
| [sorbet](https://github.com/sorbet/sorbet) | Type checker for Ruby |
| [tapioca](https://github.com/Shopify/tapioca) | RBI file generator for Sorbet |
| [spoom](https://github.com/Shopify/spoom) | Tools for Sorbet |
| [prism](https://github.com/ruby/prism) | Ruby parser |
| [low_type](https://github.com/low-rb/low_type) | Elegant types for Ruby |
| [dry-monads](https://github.com/dry-rb/dry-monads) | Idiomatic monads for Ruby |
| [dry-validation](https://github.com/dry-rb/dry-validation) | Type-safe data validation |
| [dry-initializer](https://github.com/dry-rb/dry-initializer) | DSL for class initializers |

## 31. Modularization & Architecture

| Gem | Description |
|-----|-------------|
| [packwerk](https://github.com/Shopify/packwerk) | Packages for code modularization |
| [packs](https://github.com/rubyatscale/packs) | Extensible packaging specification |
| [packs-rails](https://github.com/rubyatscale/packs-rails) | Packs integration for Rails |
| [code_ownership](https://github.com/rubyatscale/code_ownership) | Code ownership declarations |
| [interactor](https://github.com/collectiveidea/interactor) | Interactor design pattern |

## 32. CLI & Tools

| Gem | Description |
|-----|-------------|
| [thor](https://github.com/rails/thor) | Toolkit for building command-line interfaces |
| [tmuxinator](https://github.com/tmuxinator/tmuxinator) | Manage tmux sessions easily |
| [rubyshell](https://github.com/albertalef/rubyshell) | Write shell scripts in Ruby |
| [rv](https://github.com/spinel-coop/rv) | Fast Ruby version manager (written in Rust) |
| [trace_location](https://github.com/yhirano55/trace_location) | Trace source code locations |

## 33. QR Codes, Calendar & Misc Utilities

| Gem | Description |
|-----|-------------|
| [rqrcode](https://github.com/whomwah/rqrcode) | QR code generator |
| [add_to_calendar](https://github.com/jaredlt/add_to_calendar) | "Add to Calendar" URL helpers |
| [simple_calendar](https://github.com/excid3/simple_calendar) | Simple calendar view for Rails |
| [fugit](https://github.com/floraison/fugit) | Time tools (cron parsing, durations, etc.) |
| [refer](https://github.com/excid3/refer) | Referral codes for Rails |
| [sqids-rails](https://github.com/tbhb/sqids-rails) | Sqids (Hashids) for Rails |
| [globalid](https://github.com/rails/globalid) | Identify app models with a URI |
| [chartkick](https://github.com/ankane/chartkick) | Create charts with one line of Ruby |
| [wikipedia-client](https://github.com/kenpratt/wikipedia-client) | Wikipedia API client |
| [xsv](https://github.com/martijn/xsv) | Fast .xlsx parser |

## 34. Asset Pipeline

| Gem | Description |
|-----|-------------|
| [propshaft](https://github.com/rails/propshaft) | Asset delivery for Rails |

## 35. Ruby Implementations & Compatibility

| Gem | Description |
|-----|-------------|
| [ruby](https://github.com/ruby/ruby) | The Ruby programming language |
| [jruby](https://github.com/jruby/jruby) | Ruby on the JVM |
| [truffleruby](https://github.com/truffleruby/truffleruby) | Ruby on GraalVM |
| [ruby.wasm](https://github.com/ruby/ruby.wasm) | Ruby compiled to WebAssembly |
| [ruby-next](https://github.com/ruby-next/ruby-next) | Use modern Ruby features in older versions |
| [bootboot](https://github.com/Shopify/bootboot) | Dual boot Ruby applications |
| [deprecation_toolkit](https://github.com/Shopify/deprecation_toolkit) | Track and eliminate deprecation warnings |
| [end_of_life](https://github.com/MatheusRich/end_of_life) | Detect end-of-life software |
| [gvltools](https://github.com/Shopify/gvltools) | GVL instrumentation tools |

## 36. Cross-language & Interop

| Gem | Description |
|-----|-------------|
| [crystalruby](https://github.com/wouterken/crystalruby) | Embed Crystal code in Ruby |
| [rutie](https://github.com/danielpclark/rutie) | Ruby-Rust bridge |
| [ruby-libgd](https://github.com/ggerman/ruby-libgd) | Native GD graphics bindings |
| [RatatuiRuby](https://github.com/setdef/RatatuiRuby) | Ratatui wrapper for terminal UIs in Ruby |
| [iruby](https://github.com/SciRuby/iruby) | Ruby kernel for Jupyter notebooks |

## 37. Real-World Apps (Open Source)

| App | Description |
|-----|-------------|
| [mastodon](https://github.com/mastodon/mastodon) | Federated social network |
| [discourse](https://github.com/discourse/discourse) | Community discussion platform |
| [maybe](https://github.com/maybe-finance/maybe) | Personal finance app |
| [gumroad](https://github.com/antiwork/gumroad) | Sell digital products |
| [fizzy](https://github.com/basecamp/fizzy) | Kanban board |
| [once-campfire](https://github.com/basecamp/once-campfire) | Group chat |
| [stemplin](https://github.com/rubynor/stemplin) | Time tracking |

## 38. Style Guides & Best Practices

| Resource | Description |
|----------|-------------|
| [ruby-style-guide](https://github.com/rubocop/ruby-style-guide) | Community-driven Ruby style guide |
| [rails-style-guide](https://github.com/rubocop/rails-style-guide) | Community-driven Rails style guide |
| [rspec-style-guide](https://github.com/rubocop/rspec-style-guide) | Community-driven RSpec style guide |
| [ruby (Airbnb)](https://github.com/airbnb/ruby) | Airbnb's Ruby style guide |
| [ruby-style-guide (Shopify)](https://github.com/Shopify/ruby-style-guide) | Shopify's Ruby style guide |
| [secure_rails](https://github.com/ankane/secure_rails) | Rails security best practices |
| [production_rails](https://github.com/ankane/production_rails) | Rails in production best practices |
| [rails_standards](https://github.com/hopsoft/rails_standards) | Rails coding standards |
| [design-patterns-in-ruby](https://github.com/design-patterns-in-ruby/design-patterns-in-ruby) | Design patterns implemented in Ruby |
| [ruby-science](https://github.com/thoughtbot/ruby-science) | Reference for growing Rails applications |

## 39. Learning & Resources

| Resource | Description |
|----------|-------------|
| [awesome-ruby](https://github.com/markets/awesome-ruby) | Curated collection of Ruby resources |
| [real-world-ruby-apps](https://github.com/jeromedalbert/real-world-ruby-apps) | Real-world Ruby applications |
| [real-world-rails](https://github.com/eliotsykes/real-world-rails) | Real-world Rails applications |
| [awesome-ruby-blogs](https://github.com/Yegorov/awesome-ruby-blogs) | Collection of Ruby blogs |
| [engineering-blogs](https://github.com/kilimchoi/engineering-blogs) | Engineering blogs from top companies |
| [ruby-warrior](https://github.com/ryanb/ruby-warrior) | Game for learning Ruby |
| [prep-test](https://github.com/ruby-association/prep-test) | Ruby certification prep |
| [planetruby](https://github.com/peterc/planetruby) | Ruby blog aggregator |
| [how-to-build-desktop-applications-in-ruby](https://github.com/AndyObtiva/how-to-build-desktop-applications-in-ruby) | Build desktop apps with Ruby |
| [libgd-gis](https://github.com/ggerman/libgd-gis) | GIS with Ruby and libGD |
| [dev-meeting-log](https://github.com/ruby/dev-meeting-log) | Ruby core developer meeting logs |
| [ruby-definitions](https://github.com/Shopify/ruby-definitions) | Shopify's Ruby build definitions |

## 40. Rails-specific Dev Tools & Skills

| Resource | Description |
|----------|-------------|
| [claude-on-rails](https://github.com/obie/claude-on-rails) | Claude framework for Rails developers |
| [rails-claude-code](https://github.com/maquina-app/rails-claude-code) | Rails skills for Claude Code |
| [ruby-skills](https://github.com/st0012/ruby-skills) | Claude skills for Ruby |
| [skills](https://github.com/palkan/skills) | Skills based on Layered Rails |
| [rails-audit-thoughtbot](https://github.com/thoughtbot/rails-audit-thoughtbot) | Rails code audit tool |
| [cursor-rails-rules](https://github.com/wintermeyer/cursor-rails-rules) | Cursor rules for Rails |
| [superpowers-rails](https://github.com/marostr/superpowers-rails) | Superpowers with Rails features |

## 41. Rails DOM & Testing Helpers

| Gem | Description |
|-----|-------------|
| [rails-dom-testing](https://github.com/rails/rails-dom-testing) | DOM assertions for Rails views |
| [rails-controller-testing](https://github.com/rails/rails-controller-testing) | `assigns` and `assert_template` for Rails controllers |
| [rails-observers](https://github.com/rails/rails-observers) | Observers extracted from Rails 4 |
| [rails-training-testing-exercise](https://github.com/thoughtbot/rails-training-testing-exercise) | Testing exercises for Rails |
| [action_dispatch-testing-integration-capybara](https://github.com/thoughtbot/action_dispatch-testing-integration-capybara) | Capybara integration for ActionDispatch |
| [hotwire-example-template](https://github.com/thoughtbot/hotwire-example-template) | Hotwire example templates |

---

## Contributing

Contributions are welcome! If you know of a great Ruby gem or Rails library that should be listed here, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
