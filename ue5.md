# Moving Actor
Timer += DeltaTime;

FVector NewLocation = GetActorLocation();

NewLocation.Y += FMath::Cos(Timer);

SetActorLocation(NewLocation);
