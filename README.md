## beam-go
### rehana naguru
Create a folder beam-go
'''
go mod init github.com/rehana7/beam-go  
'''
go install github.com/apache/beam/sdks/v2/go/examples/wordcount

wordcount --input sample.txt --output counts
