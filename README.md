# Running the programs

To begin, make sure you have [.NET Core](https://www.microsoft.com/net/core/platform) and [RabbitMQ](https://www.rabbitmq.com/download.html) installed.

Open three terminals.

Run two workers using separate terminals:

```
dotnet run -p Worker
```

Then publish some tasks in the other terminal:

```
dotnet run -p NewTask "First message."
dotnet run -p NewTask "Second message.."
dotnet run -p NewTask "Third message..."
dotnet run -p NewTask "Fourth message...."
dotnet run -p NewTask "Fifth message....."
```
