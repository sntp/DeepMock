# DeepMock

Mocking framework capable to be used as:

    @Mock
    MyObject object;
    
    ...
    
    when(object.getChild().callSomeMethod("some", "parameters").getList().get(5).getName()).thenReturn("Response")
