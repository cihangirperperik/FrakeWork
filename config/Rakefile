# -*- encoding: utf-8 -*-
task :default => ["run_server"]

desc "Run local server"
task :run_server do
  system %{
    source config/server.sh
    server
  }
end
