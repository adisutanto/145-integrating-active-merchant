Railscasts Episode #145: Integrating Active Merchant

http://railscasts.com/episodes/145

Commands

    bundle install

    rails generate nifty:scaffold order new cart_id:integer ip_address:string first_name:string last_name:string card_type:string card_expires_on:date
  
    rails generate model order_transaction order_id:integer action:string amount:integer success:boolean authorization:string message:string params:text
