for(String list: itemList){
            if(!priceSet.containsKey(list))
                System.out.println("sorry! we are out off this pariticular " + list);
            else
                //System.out.println(list);
               // for(String name:priceSet.keySet()) {
                   // if (item.equalsIgnoreCase(list))
                    price1 = priceSet.get(list);
                    int quntity =1+ rand.nextInt(10);
                    System.out.println(quntity);
                    System.out.println(price1);
                    totalprice = quntity*price1;
                    System.out.println(totalprice);

                //}
        }
