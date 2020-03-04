[
  {
    "users":[
      {
        'repeat(100, 100)': {
            _id: '{{objectId()}}',
            index: '{{index()}}',
            name: {
              first: '{{firstName()}}',
              last: '{{surname()}}'
            },
          	students: [
              {
              	'repeat(5, 6)': '{{integer(5, 100)}}'
              }
            ],
            city: '{{random("London", "Manchester", "Liverpool")}}',
        }
      }
    ],
    "profile": {
        "name": "typicode"
    }
  }
]
