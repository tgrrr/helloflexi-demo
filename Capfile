# Load DSL and Setup Up Stages
require 'capistrano/setup'

# Includes default deployment tasks
require 'capistrano/deploy'
require 'capistrano/rvm'
require 'capistrano/ssh_doctor'
require 'capistrano/bundler'
#require 'capistrano/rails/assets'
require 'capistrano/rails/migrations'
require 'capistrano/puma'
#require 'capistrano/rails/migrations'
#require 'capistrano/puma'
# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.

set :stage, :production

Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }