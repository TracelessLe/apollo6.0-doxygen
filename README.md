# apollo6.0-doxygen
Apollo 6.0 Project Doxygen Documentation

# Homepage

```
./html/index.html

or

https://tracelessle.github.io/apollo6.0-doxygen/html/index.html
```

# How to generate from apollo project
1. clone Apollo project

2. jump into the apollo docker env and build the project

```
username@in-dev-docker:/apollo# 
```

3. install dependence packages

```
sudo apt-get install graphviz graphviz-doc
sudo apt-get -y install doxygen
```

3. modify `apollo.doxygen`
```
username@in-dev-docker:/apollo# vim apollo.doxygen
```

```
PROJECT_NUMBER         = 2.0  ->   PROJECT_NUMBER         = 6.0
```

4. run generate script

```
bash scripts/apollo_docs.sh generate
```

Enjoy it when the message below is printed on the screen!
```
==============================================
***
[ OK ] Apollo docs generated. Time taken: 120s
==============================================
```
