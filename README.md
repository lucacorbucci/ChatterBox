# ChatterBox

**Operating Systems and Laboratory** Project @ Unipi.
Academic year 2016/2017.

The text of the project is available here: http://didawiki.di.unipi.it/doku.php/informatica/sol/laboratorio17/progetto and in the "Testo Progetto" folder in the repo.
A final report is available in the "Report" folder.

### How to try Chatterbox

To test the project:

```
git clone https://github.com/lucacorbucci/ChatterBox.git
cd Chatterbox
make
```

Then you can launch the server using the command:

```
./chatty -f ./DATA/chatty.conf1
```

You can run the client using the following command:

```
./client -l /tmp/chatty_socket -c luca
```

There are some flags useful to configure and use the client.

### Test

In the folder Test you can find some tests that can be used to try the Project.

