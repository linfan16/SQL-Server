# SQL-Server A studentClass database will be established using SQL Server Scripts
USE [master]
GO

/****** Object:  Database [dbtest]    Script Date: 2021/9/30 10:41:08 ******/
CREATE DATABASE [dbtest1]
ON  PRIMARY 
( NAME = N'dbtest1', FILENAME = N'D:\Program Files\Microsoft SQL Server\MSSQL15.MSSQLSERVER\MSSQL\DATA\dbtest1.mdf' , SIZE = 5MB , MAXSIZE = UNLIMITED, FILEGROWTH = 15% )
LOG ON 
( NAME = N'dbtest1_log', FILENAME = N'D:\Program Files\Microsoft SQL Server\MSSQL15.MSSQLSERVER\MSSQL\DATA\dbtest1_log.ldf' , SIZE = 2MB , MAXSIZE = 40GB , FILEGROWTH = 1MB )
GO
