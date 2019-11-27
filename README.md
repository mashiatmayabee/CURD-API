
Documentation of the API:
# mayaapi


get all products:
https://mayaapi.herokuapp.com/products
get one product by id :
https://mayaapi.herokuapp.com/products/<product id>

example :
https://mayaapi.herokuapp.com/products/5dde2049e883b01ef0ce036d


post a prodcut
https://mayaapi.herokuapp.com/products
JSON file:
{
	"title": "<String>",	
	"description" :"<string>",
	"price" : <number>,
	"company" : "<String>"
}
example:
{
        "_id": "5dde2049e883b01ef0ce036d",
        "title": "virtual bro",
        "description": "bee",
        "price": 45,
        "company": "HP",
        "createdAt": "2019-11-27T07:05:45.062Z",
        "updatedAt": "2019-11-27T07:05:45.062Z",
        "__v": 0
 }
    

delete a product
https://mayaapi.herokuapp.com/products/<product id>
example:
https://mayaapi.herokuapp.com/products/5dde2049e883b01ef0ce036d
