Changed all functions in the `ArmMemoryInterface` trait that return something involving the `ArmCommunicationInterface` type and replace them with calls that return generic traits. Adapted all functions that relied on the old calls to use the new calls instead.