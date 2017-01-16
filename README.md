# Scope

Scope of this project is a first evaluation with github and all the cool stuff out there....

## Second change

adding some extra text here

## Some graphics

Check out the following sequence diagram

![Alt text](http://g.gravizo.com/g?
@startuml;
(*) --> if "Some Test" then;
  -->[true] "activity 1";
  if "" then;
   -> "activity 3" as a3;
  else;
    if "Other test" then;
      -left-> "activity 5";
    else;
      --> "activity 6";
    endif;
  endif;
endif;
@enduml 
)
