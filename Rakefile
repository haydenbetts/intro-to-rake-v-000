namespace :greeting do

  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hello to the terminal in spanish'
  task :hola do
    puts "hola de Rake!"
  end

end

namespace :db do

  desc 'performs migration'
  task :migrate do

  end

  desc 'seeds db'
  task seed do
    require_relative './db/seeds'
  end
end
