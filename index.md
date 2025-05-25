# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

![My cat image](https://octodex.github.com/images/yaktocat.png)

This is my code block
```terraform
resource "aws_instance" "myserver" {
  ami           = "ami-830c94e3"
  instance_type = "t2.micro"

  security_groups = []

  tags = {
    Name = "thy-server"
  }
}
```
