<template>
  <CRow>
    <CCol>
      <h1>PROFIL PEGAWAI</h1>
      <CCard class="mb-4">
        <CCardHeader><b>Jabatan Fungsional Pranata Komputer </b></CCardHeader>
        <CCardBody>
          <CForm>
            <CFormInput
              type="text"
              id="formControlNama"
              label="Nama Pegawai"
              text=""
              aria-describedby="formControlNama"
            />
          </CForm>
          <CForm class="mt-2 mb-2">
            <CFormInput
              type="text"
              id="formControlNip"
              label="NIP"
              aria-describedby="formControlNip"
            />
          </CForm>

          <CForm class="mt-2 mb-2">
            <label>Jabatan</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Pilih Jabatan',
                { label: 'Ahli Pertama', value: '1' },
                { label: 'Ahli Muda', value: '2' },
                { label: 'Ahli Madya', value: '3' },
                { label: 'Ahli Utama', value: '4' },
              ]"
            >
            </CFormSelect>
          </CForm>
          <CForm>
            <CFormInput
              type="text"
              id="formControlUnit"
              label="Unit kerja"
              aria-describedby="formControlUnit"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="text"
              id="formControlSatuan"
              label="Satuan kerja"
              aria-describedby="formControlSatuan"
            />
          </CForm>
          <br />
          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
