<RTIAgent>
  <Location>
    <LocationDescription />
  </Location>
  <AgentVariables import="">
    <AgentVariable name="StagingDBName" value="MyDatabase" />
    <AgentVariable name="StagingDBServer" value="StagingDatabaseName" />
  </AgentVariables>
  <Instructions>
    <Instruction>
      <Priority>2</Priority>
      <HostAccount />
    </Instruction>
    <Instruction>
      <Priority>2</Priority>
      <HostAccount>some other new Account Details</HostAccount>
      <BatchSize>1</BatchSize>
    </Instruction>
    <Instruction>
      <HostAccount>some other new Account Details</HostAccount>
    </Instruction>
  </Instructions>
</RTIAgent>
