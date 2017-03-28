<p>This is my entry for the sortable coding challenge: https://sortable.com/challenge/.
It's not perfect, but the deadline is coming up and I have other things to get to.
It is written in Go (or Golang if you will), which I have no previous experience with. It was a fun learning experience.</p>

<p>To run this on Ubuntu or other similar linux systems you need to have git and go installed</p>

<p>To install git, run: sudo apt install git</p>

<p>To install go, run: wget https://storage.googleapis.com/golang/go1.8.linux-amd64.tar.gz; sudo tar -C /usr/local -xzf go1.8.linux-amd64.tar.gz; sudo cat "PATH=$PATH:/usr/local/go/bin" >> /etc/profile; export PATH=$PATH:/usr/local/go/bin</p>

<p>To clone my repo, run: mkdir -p ~/go/src/github.com/Scalu; cd ~/go/src/github.com/Scalu; git clone https://github.com/Scalu/sortablechallenge.git</p>

<p>To build and run my code, run: cd ~/go/src/github.com/Scalu/sortablechallenge; go build; ./sortablechallenge</p>

