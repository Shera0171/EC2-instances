# EC2 instance.
Start an Amazon Web Services computer

Start at the Amazon Web Services console EC2 launch wizard. You’ll need to sign in to EC2.

Click on “Launch instance.”

# Please click the below you tube link.


```bash
https://www.youtube.com/watch?v=904cW9lJ7LQ
```

## For usage 

* Change the .pem below
* and make two bash terminal and run the below code in 1_bash(local) and 2_bash(EC2)

```bsah
sudo scp -i "Shreyansh_practice(EC2).pem" app.py ec2-user@ec2-44-202-146-126.compute-1.am
azonaws.com:/home/ec2-user/
```
```bash
sudo scp -i "Shreyansh_practice(EC2).pem" requirements.txt ec2-user@ec2-44-202-146-126.compute-1.amazonaws.com:/home/ec2-user/
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
