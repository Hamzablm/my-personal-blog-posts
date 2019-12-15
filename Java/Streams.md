# Lambdas, functional interfaces

## Chaining lambdas with default methods
### Consumer interface
### Predicate interface

## Composing lambdas
### Comparator interface
```java
        Comparator<Person> cmp = Comparator.comparing(Person::getLastName)
                        .thenComparing(Person::getFirstName)
                        .thenComparing(Person::getAge);
```

## Partial Application
### Currently converter example

# Comparators

# Streams

# Collectors
