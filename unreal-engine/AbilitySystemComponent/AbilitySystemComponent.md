![[unreal-engine/AbilitySystemComponent/screenshot_01.png]]
```cpp
PROPERTY()  
TObjectPtr<UAbilitySystemComponent> AbilitySystemComponent;
```

```cpp title:constructor
AbilitySystemComponent = CreateDefaultSubobject<UAuraAbilitySystemComponent>(TEXT("AbilitySystemComponent"));
```