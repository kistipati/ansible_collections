Scope
The IBM Power Systems AIX collection provides modules that can be used to manage configurations and deployments of Power AIX systems. The collection content helps to include workloads on Power platforms as part of an enterprise automation strategy through the Ansible ecosystem.

The IBM Power Systems AIX collection is included as an upstream collection under the Ansible Content for IBM Power Systems umbrella of community content.

Join the Power Research Program
Become an IBM Power Design Partner. Engage with our Power Research team across various research studies to shape the future of Anisble on Power: https://ibm.biz/BdyRyk

Usage
This repository contains some example best practices for open source repositories:

LICENSE
README.md
CONTRIBUTING.md
MAINTAINERS.md
CODE_OF_CONDUCT.md for more details you should read this.
travis.yml - Look https://docs.travis-ci.com/user/tutorial/ for more details.
Requirements
AIX 7.3 will require additional software only for the flrtvc, nim_flrtvc and nim_vios_hc AIX Ansible Collection's modules. Additional open-source software is installed by configuring [DNF] first. YUM only supports Python2.
Modules flrtvc and nim_flrtvc requires wget. See demo playbooks examples.
Module nim_vios_hc software requirements will be automatically installed using power_aix_vioshc role. See demo playbook examples.
Platforms
AIX 7.1
AIX 7.2
AIX 7.3
Ansible
Requires Ansible 2.9 or newer
For help installing Ansible, refer to the Installing Ansible section of the Ansible Documentation
For help installing the ibm.power_aix collection, refer to the install page of this project
Python
Requires Python 3.8 or newer
To install (or upgrade) Python on AIX 7.1 and 7.2, you must first configure YUM. As part of YUM installation, Python2 will be installed by default.
After setting up and installing YUM, you may update all the packages to the latest level using the yum update command.
AIX 7.3 will come with Python3 pre-installed. Ansible will work with AIX 7.3 with no need for additional software.
Resources
Documentation of modules is generated on GitHub Pages.

Question, Issue or Contribute
If you have any questions or issues you can create a new issue here.

Pull requests are very welcome! Make sure your patches are well tested. Ideally create a topic branch for every separate change you make. For example:

Fork the repo
Create your feature branch (git checkout -b my-new-feature)
Commit your changes (git commit -am 'Added some feature')
Push to the branch (git push origin my-new-feature)
Create new Pull Request
License & Authors
If you would like to see the detailed LICENSE click here.

Copyright:: 2021- Capgemini, Inc

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
Authors:
