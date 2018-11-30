# Uranus FIXM

参考[ICAO FIXM模型](https://www.fixm.aero/)来创建的FlightObject

## ICAO FIXM
### Base
#### Address
- ContactInformation
    - name
    - title
    - OnlineContact
    - PostalAddress
    - TelephoneContact

#### Aerodrome
#### Airspace
#### Measures
#### Navaid
#### Organization
#### RangesAndChoices
#### Types



### Flight
- 
#### Aircraft
##### 从CAT62中
- TargetAddress
    - 飞行器24位的唯一编码
    - Integer address
- TargetIdentification
    - 飞行器呼号 如CCA4414
    - String identification
- MagneticHeading
    - 磁航向
    - Double degree
- IndicatedAirspeed
    - Uom KT/MACH
    - Double speed
- TrueAirspeed
    - Uom KT
    - Double speed
- SelectedAltitude
    - Uom FEET
    - Source UNKNOWN/AIRCRAFT/FCU/FMS
    - Double altitude
- FinalStateSelectedAltitude
    - VerticalMode ACTIVE/NOT_ACTIVE
    - AltitudeHold ACTIVE/NOT_ACTIVE
    - ApproachMode ACTIVE/NOT_ACTIVE
    - Double Altitude
- StatusByAdsBroadcast
    - AC MN DC GBS
    - STAT
- AcasResolutionAdvisoryReport
    - report
- BarometricVerticalRate
    - rate
- GeometricVerticalRate
    - rate
- RollAngle
    - angle
- TrackAngleRate
    - Direction LEFT/RIGHT/STRAIGHT/NOT_AVAILABLE
    - rate
- TrackAngle
    - angle
- GroundSpeed
    - speed
- VelocityUncertainty
    - category
- MetData
    - windSpeed
    - windDirection
    - temperature
    - turbulence
- EmitterCategory
- Position
    - latitude
    - longitude
- GeometricAltitude
    - altitude
- PositionUncertainty
- ModeSelectiveMbData
    - data
- IndicatedAirspeed
- MachNumber
- BarometricPressureSetting

##### FDEXM中
- AircraftType
- AircraftRegistration
- Capability
    - nav
    - sur
        - modeACode
    - com
    - fleet
- WakeTurbulence
#### Arrival
#### Capability
#### Cargo
#### Departure
#### Emergency
#### Enroute
#### FlightData
#### FlightRouteTrajectory
#### RankedTrajectory


### Messaging


