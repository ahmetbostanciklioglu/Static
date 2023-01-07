# Static


**Static**

struct StaticStruct {
    var property: String
    static var property2: Int = 2
    init(property: String) {
        self.property = property
        Static.property2  += 2
    }
}
let staticObject1 = StaticStruct(property: "Ahmet")
let staticObject2 = StaticStruct(property: "Alex") 

print(staticObject1.property)
print(StaticStruct.property2) // statics are like type for StaticStruct structure. 

