#
# Cookbook Name:: apache_cookbook
# Recipe:: default
#
# Copyright 2016, YOUR_COMPANY_NAME
#
# All rights reserved - Do Not Redistribute
#

package "apache2" do
	case node[:platform]
	when "centos","redhat","fedora","amazon"
	package_name "httpd"
	when "debian","ubuntu"
	package_name "apache2"
	end
	action :install

end
