primes: List[int] = []

captain: str  # Note: no initial value!

class Starship:
     stats: Dict[str, int] = {}

     
Just as for function annotations, the Python interpreter does not attach any particular meaning to variable annotations and only stores them in a special attribute __annotations__ of a class or module. In contrast to variable declarations in statically typed languages, the goal of annotation syntax is to provide an easy way to specify structured type metadata for third party tools and libraries via the abstract syntax tree and the __annotations__ attribute.

![image](https://github.com/Karlie-crypto/alx-backend-python/assets/110098940/8d743950-2736-4aa4-ac0e-32827ac8aaca)
