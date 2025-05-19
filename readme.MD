## Selectors

taint node

'''
kubectl taint nodes ip-192-168-21-179.ec2.internal hardware=gpu:NoSchedule

'''

# To remove the taint - kubectl taint nodes node1 key1=value1:NoSchedule-