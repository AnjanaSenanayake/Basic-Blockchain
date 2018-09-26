# Basic-Blockchain
This a example of a basic blockchain implementation

# Dependencies
Flask

# How to resolve Dependencies
From terminal

      - pip install Flask==0.12.2
      
# How to Run

1). Run blockchain.py

2). Use Postman(or likewise)

       - [GET]localhost:5000/get_chain
       - [POST]localhost:5000/add_transaction 
           >> include a relevant json object with: (item_name,transaction_date,current_owner,previous_owner,transaction_amount)          
       - [GET]localhost:5000/mine_block
       - [POST]localhost:5000/connect_node
       - [GET]localhost:5000/replace_chain
    
# Reference
https://github.com/harrywang/blockchain-hackernoon
       
