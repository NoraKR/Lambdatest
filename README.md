import os

def lambda_handler(event, context):
    os.system('cat /etc/os-release')
    os.system('pwd')
    os.system('ls -l')
    os.system('cat lambda_function.py')
