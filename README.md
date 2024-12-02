# Virtual_Machine
Virtual Machine / Codigo / Ollama 



<VirtualBox xmlns="http://www.virtualbox.org/" version="1.19-windows">
  <Machine uuid="{b8d3228a-3e02-4fac-b6e7-e8183799808e}" name="vector" OSType="Windows10_64" snapshotFolder="Snapshots" lastStateChange="2024-12-01T21:14:57Z" aborted="true">
    <MediaRegistry>
      <HardDisks>
        <HardDisk uuid="{d1dd1a01-41f6-42bd-888d-21aa78e565ba}" location="vector.vdi" format="VDI" type="Normal"/>
      </HardDisks>
      <DVDImages>
        <Image uuid="{e57f63ba-5a0d-4e6f-b82b-25510c412f9c}" location="C:/Program Files/Oracle/VirtualBox/VBoxGuestAdditions.iso"/>
      </DVDImages>
    </MediaRegistry>
    <ExtraData>
      <ExtraDataItem name="GUI/LastNormalWindowPosition" value="363,102,640,523"/>
    </ExtraData>
    <Hardware>
      <Memory RAMSize="7694"/>
      <HID Pointing="USBTablet"/>
      <Display controller="VBoxSVGA" VRAMSize="128"/>
      <Firmware/>
      <BIOS>
        <IOAPIC enabled="true"/>
        <SmbiosUuidLittleEndian enabled="true"/>
        <AutoSerialNumGen enabled="true"/>
      </BIOS>
      <USB>
        <Controllers>
          <Controller name="XHCI" type="XHCI"/>
        </Controllers>
      </USB>
      <Network>
        <Adapter slot="0" enabled="true" MACAddress="080027DD7063" type="82540EM">
          <NAT localhost-reachable="true"/>
        </Adapter>
      </Network>
      <AudioAdapter controller="HDA" useDefault="true" driver="WAS" enabled="true" enabledOut="true"/>
      <Clipboard/>
      <GuestProperties>
        <GuestProperty name="/VirtualBox/HostInfo/GUI/LanguageID" value="es_ES" timestamp="1733025700668583100" flags=""/>
      </GuestProperties>
      <StorageControllers>
        <StorageController name="SATA" type="AHCI" PortCount="2" useHostIOCache="false" Bootable="true" IDE0MasterEmulationPort="0" IDE0SlaveEmulationPort="1" IDE1MasterEmulationPort="2" IDE1SlaveEmulationPort="3">
          <AttachedDevice type="HardDisk" hotpluggable="false" port="0" device="0">
            <Image uuid="{d1dd1a01-41f6-42bd-888d-21aa78e565ba}"/>
          </AttachedDevice>
          <AttachedDevice passthrough="false" type="DVD" hotpluggable="false" port="1" device="0">
            <Image uuid="{e57f63ba-5a0d-4e6f-b82b-25510c412f9c}"/>
          </AttachedDevice>
        </StorageController>
      </StorageControllers>
      <CPU count="2">
        <HardwareVirtExLargePages enabled="true"/>
        <PAE enabled="false"/>
        <LongMode enabled="true"/>
      </CPU>
    </Hardware>
  </Machine>
</VirtualBox>
