.. ansible-container documentation master file, created by
   sphinx-quickstart on Wed May 25 11:17:05 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to ansible-container!
=============================
Ansible Container enables you to build Docker images and orchestrate containers using only Ansible playbooks. Describe
your application in Docker Compose and, rather than a Dockerfile, provide a playbook with tasks for building images.
Ansible Container will take it from there.

With Ansible Container, you are no longer limited by Dockerfile. You can now apply the power of Ansible to the image build
process. Use templates, copy files, drop in encrypted data, handle errors, add conditionals, and more. Everything
Ansible brings to orchestrating your infrastructure can now be applied to the image build process.

But Ansible Container does not stop there. Use Ansible Container to run the application, and push images to private and
public registries. When you are ready to deploy to the cloud, use it to generate an Ansible role that automates the
deployment.


.. toctree::
   :maxdepth: 1

   installation
   quickstart
   init
   build
   push
   run
   deploy


