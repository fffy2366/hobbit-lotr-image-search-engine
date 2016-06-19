

```shell

python index.py --dataset images --index index.cpickle
python search_external.py --dataset images --index index.cpickle --query queries/rivendell-query.png


python index.py --dataset /Users/fengxuting/Downloads/0614-6_1 --index index6.cpickle
python search_external.py --dataset /Users/fengxuting/Downloads/0614-6_1 --index index6.cpickle --query /Users/fengxuting/Downloads/0614-6_1/1464319820957AB9CF69.jpg
python search_external.py --dataset /Users/fengxuting/Downloads/0614-6_1 --index index6.cpickle --query /Users/fengxuting/Downloads/0614-6_1/1464319796527A0C9732.jpg

python search.py --dataset /Users/fengxuting/Downloads/0614-6_1 --index index6.cpickle
```