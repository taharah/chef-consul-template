source "https://api.berkshelf.com"

metadata

cookbook 'apt'
cookbook 'consul'
cookbook 'libarchive'

group :test do
  cookbook 'consul-template-spec', path: 'spec/fixtures/cookbooks/consul-template-spec'
end
