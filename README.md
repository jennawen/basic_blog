Here is what we can run using tux to create data directly from the command line. 

tux
>> Post.create(title: 'Who knows about using Nest?', body: 'Does anyone have a Nest? Can I play with it?')
>>
>> Post.all
D, [2013-06-08T12:26:44.929333 #42914] DEBUG -- :   Post Load (0.2ms)  SELECT "posts".* FROM "posts" 
=> [#<Post id: 1, title: "Testing the title", body: "Lorem ipsum dolor sit amet, consectetur adipiscing ...", created_at: "2013-06-08 12:24:12", updated_at: "2013-06-08 12:24:12">]
