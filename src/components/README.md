# -*- coding: utf-8 -*-

"""
infra-terraform README file.

This file provides an overview of the infra-terraform project, its goals, and its usage.
"""

__version__ = '1.0.0'

import os

def get_project_info():
    """Return project information."""
    return {
        'name': 'infra-terraform',
        'description': 'A Terraform infrastructure project.',
        'version': __version__,
        'author': 'Your Name',
        'email': 'your@email.com'
    }

def get_project_dependencies():
    """Return project dependencies."""
    return {
        'terraform': '>= 0.14.0',
        'python': '>= 3.6'
    }

def get_project_usage():
    """Return project usage instructions."""
    return """
Usage:
  terraform init
  terraform plan
  terraform apply
"""

if __name__ == '__main__':
    print(get_project_info())
    print(get_project_dependencies())
    print(get_project_usage())