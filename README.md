# SignalRSqlServerChnageNotification
Sql Server Change notifications in ASP.NET MVC using SignalR
Change connection string in web.config with your own connection string
Run Following script in Sql Server

Create Database DemoCRM

Go

Use DemoCRM

Go

CREATE TABLE DevTest(

	[ID] [int] IDENTITY(1,1) NOT NULL,

	[CampaignName] [varchar](255) NULL,

	[Date] [datetime] NULL,

	[Clicks] [int] NULL,

	[Conversions] [int] NULL,

	[Impressions] [int] NULL,

	[AffiliateName] [varchar](255) NULL

) ON [PRIMARY]

GO

Open project in Visual Studio 2015

Restore nuget packages by right click on solution and click on Restore Nuget Packages

Run the project and Enjoy!